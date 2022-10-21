# Lemon 🍋

Experimental Scheme implementation ([R7RS-small](https://small.r7rs.org/)) that compiles to [Zig](https://ziglang.org/), as opposed to the more common C target. 

The goals of this project are to create a simple reference implementation, conform to the specification, and to experiment with a newer compile target. Although not a primary goal, it might also be interesting to have an extension language for Zig, similar to [Guile](https://www.gnu.org/software/guile/) being an extension language for C and C++.

You can learn more about the merits of Zig in the [in-depth overview](https://ziglang.org/learn/overview/) and the [Why Zig?](https://ziglang.org/learn/why_zig_rust_d_cpp/) page.

## Resources

- [PDF of the ratified R7RS-small standard](https://small.r7rs.org/attachment/r7rs.pdf).
- [Lisp In Small Pieces](https://www.cambridge.org/core/books/lisp-in-small-pieces/66FD2BE3EDDDC68CA87D652C82CF849E) is a comprehensive textbook on compiling lisps.
- [Gambit Scheme](https://github.com/gambit/gambit), an efficient Scheme that compiles to C.
- [Cheney on the MTA](https://dl.acm.org/doi/pdf/10.1145/214448.214454), paper that describes an interesting compilation technique and garbage collection mechanism.
- [Chicken Scheme](https://call-cc.org/) implements the above paper, more on it's [garbage collection internals here](https://www.more-magic.net/posts/internals-gc.html) and [the overall compilation here](https://wiki.call-cc.org/chicken-compilation-process).
- [Lambda Papers](https://en.wikisource.org/wiki/Lambda_Papers) are considered a classic for any budding Scheme enthusiast.

## Development

**Lemon** is itself implemented in Zig. There are no dependencies beyond Zig itself. See the official [getting started](https://ziglang.org/learn/getting-started/#installing-zig) page for installation instructions.

## License

[BSD-3-Clause](https://github.com/Borlaag/Lemon/blob/main/LICENSE)

```
BSD 3-Clause License

Copyright (c) 2022, Børlaag
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
