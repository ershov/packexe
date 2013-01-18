Packexe: compress executable
============================

*Packexe* takes an executable as input, compresses it and produces
a packed executable which behaves exactly likes the source one.

Why might one need *packexe* when there's *gzexe* prog?

There are few differences which may be important in some cases:

1. The resulting executable is binary.
2. Unpacker process is substituted by the original one and has the same PID.
3. There will be only one executing process (with gzexe there are two).

Checked to work on Linux, Mac OS X, FreeBSD.

