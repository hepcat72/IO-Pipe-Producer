# IO-Pipe-Producer

Version 2.02

## What is it?

Producer.pm is a module that allows you to supply a subroutine or system call to a method that returns handles on the standard outout and optionally also standard error (a.k.a. STDOUT and STDERR), which you can read and process without having to wait for the subroutine or system call to finish.  If you have (for example) to process a very large text file and perform a task on each line, but you need to perform further processing on each line as it is produced, normally you would have to wait until the subroutine or system call that does each step to return before you can continue processing.  If the subroutine or system call can be made to print its output to STDOUT (and STDERR) you can use the returned handles to continuously process each line as it's "produced".  You can chain subroutines together like this by having your subroutine itself create a Producer.  This is similar to using open() to run a system call, except that with this module, you can get a handle on STDERR and use it with subroutines as well.

## INSTALLATION

To install this module type the following:

    perl Makefile.PL
    make
    make test
    make install

## DEPENDENCIES

This module requires these other modules and libraries:

    IO::Pipe
    Carp

## COPYRIGHT AND LICENCE

This software and ancillary information (herein called "SOFTWARE") called Producer.pm is made available under the terms described here.  The SOFTWARE has been approved for release with associated LA-CC number LA-CC-05-060.

Unless otherwise indicated, this software has been authored by an employee or employees of the University of California, operator of the Los Alamos National Laboratory under Contract No. W-7405-ENG-36 with the U.S. Department of Energy.  The U.S. government has rights to use, reproduce, and distribute this SOFTWARE.  The public may copy, distribute, prepare derivative works and publicly display this SOFTWARE without charge, provided that this notice and any statement of authorship are reproduced on all copies.  Neither the government nor the university makes any warranty, express or implied, or assumes any liability or responsibility for the use of this SOFTWARE.

If SOFTWARE is modified to produce derivative works, such modified SOFTWARE should be clearly marked, so as not to confuse it with the version available from LANL.
