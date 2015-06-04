The Julia language is licensed under the MIT License. The "language" consists of the compiler (the contents of src/), most of the standard library (base/), and some utilities (most of the rest of the files in this repository). See below for exceptions.

Copyright (c) 2009-2015: Jeff Bezanson, Stefan Karpinski, Viral B. Shah, and other contributors:

https://github.com/JuliaLang/julia/contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
Julia includes code from the following projects, which have their own licenses:

LDC (for ccall/cfunction ABI definitions) [BSD-3]
MUSL (for getopt implementations on Windows) [MIT]
NetBSD (for setjmp/longjmp implementations on Windows) [BSD-3]
The Julia language links to the following external libraries, which have their own licenses:

FEMTOLISP [BSD-3]
LIBUNWIND [MIT]
LIBUV [MIT]
LLVM [BSD-3, effectively]
UTF8PROC [MIT]
Julia's standard library uses the following external libraries, which have their own licenses:

ARPACK [BSD-3]
ATLAS [BSD-3]
DSFMT [BSD-3]
OPENLIBM [MIT, BSD-2, ISC]
OPENSPECFUN [MIT, public domain]
FADDEEVA [MIT]
FFTW [GPL2+]
GMP [LGPL3+ or GPL2+]
LIBGIT2 [GPL2+ with unlimited linking exception]
MPFR [LGPL3+]
OPENBLAS [BSD-3]
LAPACK [BSD-3]
PCRE [BSD-3]
SUITESPARSE [mix of LGPL2+ and GPL2+; see individual module licenses]
The following components of Julia's standard library have separate licenses:

base/fftw.jl (see FFTW)
base/sparse/csparse.jl (LGPL-2.1+)
base/linalg/umfpack.jl (see SUITESPARSE)
base/linalg/cholmod.jl (see SUITESPARSE)
Julia builds the following libraries by default, but does not use them itself:

RMATH
Julia's build process uses the following external tools:

PATCHELF
OBJCONV
Julia bundles the following external programs and libraries on some platforms:

7-Zip
BUSYBOX
GIT
ZLIB
LIBEXPAT