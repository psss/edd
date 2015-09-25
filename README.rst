
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
The name ``edd`` is the abbreviation of EDit clipboarD.


Usage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Simple and straightforward::

    select, edd, paste

Use Ctrl-V shortcut to paste the updated text. Some applications
support the Ctrl-Shift-V keyboard shortcut for pasting clipboard
content as plain text. Try this one if the formatting is broken.


Options
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Available command line options are:

--last
    open last edited text

--list
    select text from history list

--shortcut
    set up Alt-Shift-E keyboard shortcut

Note: Shortcut has been tested with the latest gnome shell only.


Config
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Edd uses the following environment variables:

EDITOR
    set to the text editor of your choice

EDD_CONFIG
    path to the config file (default: ~/.edd)

EDD_COMMAND
    command to be executed by the keyboard shortcut

The default command is::

    gnome-terminal --command edd

Use environment variable or config file to customize it::

    EDD_COMMAND="gnome-terminal --geometry 111x44 --command edd"

Note: Run ``edd --shortcut`` to update the command afterwards.


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


Authors
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Petr Šplíchal, Branislav Blaškovič, Ryan Brown and Eva Mráková.
