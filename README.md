bin
===

Assorted command line scripts for common tasks.

aggerate
--------

Assumes that each line in the input is a `key value` pair, and aggregates
together all the values of each key. The default options assume that each
`value` is a number, and adds them all together.

coinflip
--------

Generates a random sequence of values drawn, following some probability
distribution, from a given set of elements. The default options produce
a random coin flip from a fair coin.

count
-----

Counts the number of times that each line appears repeated in the input.

escapehtml
----------

Simply passes the input through `encode_entities` in order to escape away
any characters with special meaning in HTML. This produces an output safe to
paste within an HTML document, and which will render just as plain text.
