Stringlish is a tool to find likely English strings in binary files.  It's like strings, but better.

To run it, you'll need stringlish.py and ngram.py along with a version of Python < 3, and specify
one or more filenames on the command line, e.g.,

% python stringlish.py file1

ngram.py is automagically generated from mkngram.py, but unless you want to recreate it for some
reason, then mkngram.py probably isn't of too much interest.

If you want the "interesting" parts of strings highlighted when printed, look for "uncomment for
bold output" in stringlish.py and, well, uncomment those lines.  Then, piping stringlish's output
into less(1) will show the good parts in bold.

John Aycock
aycock@ucalgary.ca
