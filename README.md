[![Build Status](https://travis-ci.org/ldc-developers/ldc.png?branch=master)](https://travis-ci.org/ldc-developers/ldc)

LDC – the LLVM-based D Compiler
===============================

The LDC project aims to provide a portable D programming language
compiler with modern optimization and code generation capabilities.

The compiler uses the official DMD frontends to support the latest
version of D2, and relies on the LLVM Core libraries for code
generation.

LDC is fully Open Source; the parts of the code not taken/adapted from
other projects are BSD-licensed (see the LICENSE file for details).

Please consult the D wiki for further information:
http://wiki.dlang.org/LDC

D1 is no longer available; see the 'd1' Git branch for the last
version supporting it.


Installation
------------

In-depth material on building and installing LDC and the standard
libraries, including experimental instructions for running LDC on
Windows, is available on the project wiki, at
http://wiki.dlang.org/Building_LDC_from_source.

If you have a working C++ build environment, CMake, a current LLVM and
libconfig++ (http://hyperrealm.com/libconfig/libconfig.html)
available, there should be no big surprises, though.

Do not forget to make sure all the submodules are up to date:

    $ cd ldc
    $ git submodule update --init

Some Linux distributions are also packaging a recent version of LDC,
so building it manually might not be necessary.


Contact
-------

The best way to get in touch with the developers is either via the
digitalmars.D.ldc forum/newsgroup/mailing list
(http://forum.dlang.org) or the #ldc IRC channel on FreeNode.

For further documentation, contributor information, etc. please see
the D wiki: http://wiki.dlang.org/LDC

Feedback of any kind is very much appreciated!
