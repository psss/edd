
==================================================================
    Edd
==================================================================

Always use your favorite text editor, anywhere.


Motivation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I'm completely addicted to using Vim for editing text. Any time
Vim is not around I feel so slow, so inefficient, so cumbersome.
Thus I created Edd who enables me to use Vim literally anywhere.


Usage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Simple and straightforward::

    [ctrl-a], ctrl-c, edd, ctrl-v


Shortcut
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To set up a keyboard shortcut Alt-Shift-E run::

    edd --shortcut

This has been tested with the latest gnome shell only.


Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Uses the following two environment variables:

* EDITOR — set to the text editor of your choice
* EDD_COMMAND — command to be executed by the keyboard shortcut

The default command is this::

    gnome-terminal --geometry 100x44+400+100 --command edd


Bugs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Fille bugs here: https://github.com/psss/edd/issues/new


Name
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Edd is an abbreviation of "EDit clipboarD".
