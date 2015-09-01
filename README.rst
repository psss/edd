
==================================================================
    Edd
==================================================================

Always use your favorite text editor, anywhere.


Motivation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I'm completely addicted to using Vim for editing text. Any time
Vim is not around I feel so slow, so inefficient, so cumbersome.
Thus I created Edd who enables me to use Vim literally anywhere.


Summary
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Edd is a tiny script which allows to easily edit content of the
clipboard with a single keyboard shortcut. In this way Edd enables
you to always use your favorite text editor, wherever you need.


Usage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Simple and straightforward::

    select, edd, paste

Use Ctrl-V shortcut to paste the updated text. Some applications
support the Ctrl-Shift-V keyboard shortcut for pasting clipboard
content as plain text. Try this one if the formatting is broken.


Options
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Available command line options are::

	 --last ........... open last edited text
	 --list ........... select text from history list
	 --shortcut ....... set up Alt-Shift-E keyboard shortcut

Shortcut has been tested with the latest gnome shell only.


Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Uses the following two environment variables:

* EDITOR — set to the text editor of your choice
* EDD_COMMAND — command to be executed by the keyboard shortcut

The default command is this::

    gnome-terminal --geometry 100x44+400+100 --command edd


Links
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Git:
https://github.com/psss/edd

Docs:
http://edd.readthedocs.org/

Issues:
https://github.com/psss/edd/issues

Releases:
https://github.com/psss/edd/releases

Copr:
http://copr.fedoraproject.org/coprs/psss/edd/


Names
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

edd is the abbreviation of EDit clipboarD.

psss is the nick of Petr Šplíchal (author).
