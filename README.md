libuv for Unikraft
=============================

This is the port of libuv as a Unikraft external library. It
depends on the following libraries that need to be added to `Makefile`
in this order:

* `pthreads`, e.g. `pthread-embedded`
* `libc`, e.g. `newlib`
* `lwip'

Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository.
