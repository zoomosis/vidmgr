# TODO

For VidMgr version 2.0:

* vm_init() should return a value in case of failure.

* Call vm_init() implicitly whenever other vm_xxx functions are called.

* Replace 'char' with 'int' for cursor positioning to allow for large
screen sizes and better compatibility with system APIs.

* Use 'const' in function prototypes where necessary.

* Remove deprecated functions.

* Port to curses (pdcurses, ncurses).

* Port to S-Lang.
