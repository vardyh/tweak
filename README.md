tweak
=====

[Tweak](http://www.chiark.greenend.org.uk/~sgtatham/tweak/) is a curses-based
hex editor created by [Simon
Tatham](http://www.chiark.greenend.org.uk/~sgtatham/) (also the creator of the
famous PuTTY). This repository is a mirror with some minor changes.

_Instructions tested on Mac OS X 10.8.4 (Mountain Lion)_

How to Build
------------

    $ git clone https://github.com/mborgerson/tweak
    $ make tweak

How to Build & Install
----------------------

    $ make
    $ sudo make install

__Note:__ The default binary installation path is `/usr/local/bin/tweak` and
the man installation path is `/usr/local/man/man1/tweak.1`. You may need to add
`/usr/local/bin` and `/usr/local/man` to your `PATH` and `MANPATH` environment
variables, respectively.

How to Run
----------

    $ tweak <file>

How to Use
----------
Full documentation is available in the manpage (also available
[online](http://www.chiark.greenend.org.uk/~sgtatham/tweak/manpage-3.01.html)):

    $ man tweak

Here are the basic commands to get you started (mostly Emacs standard):

  * Arrow keys to move around (or usual Emacs)
  * `[C-x c-c]` to exit
  * `[c-x c-i]` to toggle between insert/replace mode
  * `[c-x c-s]` to save
  * `[C-x g]` to go to a byte offset in the file
  * `[Enter]` to toggle between hex and ascii
