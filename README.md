VidMgr provides a set of screen drawing, cursor and keyboard routines
for text mode MS-DOS, OS/2 and Windows 95/NT applications.

# HISTORY

VidMgr began life in March 1996 and provided support for a
limited set of DOS and OS/2 compilers. Two months later, the
first "official" version was released and provides support for a
number of additional compilers, as well as support for 32-bit
MS-DOS programs compiled with EMX. A Windows 95/NT module was
also added.

Version 1.2, the second public release of the VidMgr library,
provided support for internal "timeslicing" (CPU sharing) when
polling the keyboard using the vm_kbhit() function in an MS-DOS
application. VidMgr now also supports the DESQview "video
buffer", although this has not been tested very thoroughly. The
C source for these functions can be found in opsys.c.

Version 1.2 of VidMgr also contained a few minor modifications to
allow compilation using the Cygnus GNU C compiler for Windows
95/NT.

Version 1.3 corrects a number of minor bugs in the vm_painteol(),
vm_cleareol(), vm_paintcleareol() and vm_filleol() functions. The
Windows NT module, vmgrwnt.c, now supports the Ctrl+Left and
Ctrl+Right key combinations.


# SUPPORTED COMPILERS

The following compilers have been tested compiling the VidMgr library:

* Borland C++ (16-bit) for DOS 3.1
* Borland C++ (16-bit) for DOS 4.5
* Borland C++ (32-bit) for OS/2 1.0
* Cygnus GNU C (32-bit) for Windows 95/NT b14.0
* DJGPP GNU C (32-bit) for DOS 2.0
* EMX GNU C (32-bit) for OS/2 & DOS 0.9b
* IBM VisualAge C/C++ 3.0 (32-bit) for OS/2
* Microsoft C/C++ (16-bit) for OS/2 6.00a
* Microsoft C/C++ (16-bit) for DOS 8.00c
* Microsoft Quick C (16-bit) for DOS 2.50
* Microsoft Visual C/C++ (16-bit) for DOS 1.52
* WATCOM C/C++ (16-bit & 32-bit) for DOS 9.5
* WATCOM C/C++ (16-bit & 32-bit) for DOS 10.0
* WATCOM C/C++ (32-bit) for OS/2 10.0
* WATCOM C/C++ (32-bit) for Windows 95/NT 10.0
* HI-TECH Pacific C (16-bit) for DOS 7.51
* Symantec C/C++ (16-bit) for DOS 7.0
* Zortech C/C++ (16-bit) for DOS 3.0r4


# COPYRIGHT

The VidMgr source code was written by Andrew Clarke and released
to the public domain.
