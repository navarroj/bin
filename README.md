bin
===

Assorted command line scripts for common tasks.

aggerate
--------

Assume that each line in the input is a `key value` pair, and aggregate
together all the values of each key. The default options assume that each
`value` is a number, and adds them all together.

coinflip
--------

Produce a random sample of values from a given probability distribution. The
default options produce a random coin flip from a single fair coin.

count
-----

Count the number of times that each line appears repeated in the input.
By default the output is sorted showing the most common values first.

escapehtml
----------

Pass the input through `encode_entities` to escape away any characters with
special meaning in HTML. This produces an output safe to paste within the
source of an HTML document, which will render just as plain text.

exts
----

Given a list of files as input, output a list of all their file extensions.
The extension of a file is considered to be anything from the first dot to the
end of the file name. The list of files can be read from standard input (the
default) or from a directory in the system.

gremlins
--------

From the given input files, or standard input if no file name is given,
output every line containing non-standard ASCII characters.
