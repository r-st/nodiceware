NoDiceware
==========

Create [Diceware](http://world.std.com/~reinhold/diceware.html) passphrases easily.

Dependencies
------------
- Python3
- opterator (https://github.com/buchuki/opterator/)
- pycrypto for generating dice rolls

**WARNING:** If you need really strong passphrases roll your dice and don't use generated dice rolls.

**WARNING:** If you enter your dice rolls as the parameter, it may remain in your shell history. Don't use this option when generating secret passphrases.

Alternative word lists
----------------------
You can use your own word lists in the following form: (rolls) (word)\n
If you want to use automatically generated dice rolls, you have to use 8k word lists which have the same form or are just one word per line.
Take a look at (Diceware homepage)[http://world.std.com/~reinhold/diceware.html] for more examples of word lists.