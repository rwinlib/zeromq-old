This build is compiled with SJLJ for the old 4.6.3 toolchain.

Note that both libzmq and the driver must be compiled with

  CXXFLAGS=-DZMQ_STATIC

In order to link statically.