
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

    select, edd, ctrl-v


Options
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Available command line options are::

	 --last ............... open last edited text
	 --list ............... select text from history list
	 --shortcut ........... set up alt-shift-e keyboard shortcut

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

Project page:
https://psss.fedorapeople.org/edd/

Download:
http://psss.fedorapeople.org/edd/download/

Copr repo:
http://copr.fedoraproject.org/coprs/psss/edd/

Git repo:
https://github.com/psss/edd

File issues:
https://github.com/psss/edd/issues/new


Names
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

edd is the abbreviation of EDit clipboarD.

psss is the nick of Petr Šplíchal (author).
