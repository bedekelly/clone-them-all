CloneAll
==============

Clones and updates a user's repositories.

###Usage:
	python cloneall.py [-a|--all] [-u username] [--no-curses]

If the -a or --all flag is not set, the script will ask about each repository in turn.

If the --no-curses option is given, the program will use the standard input method.

If --no-curses is not given, the program defaults to using Curses if installed, falling
back to the standard method if necessary.

If the username is not given, the program will ask for it to be entered.

Example Usage:

[![asciicast](https://asciinema.org/a/10136.png)](https://asciinema.org/a/10136)

###Wishlist:

* Add "update repository" feature  ✓
* Add "update all" option ✓
* Support more than 100 repositories per user
* Add ncurses front-end ✓
* Add checks for git, python version etc. ✓
