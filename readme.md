This build is compiled with SEH/DRAWF for the new 4.9.3 toolchain.

Note that both libzmq and the driver must be compiled with

  CXXFLAGS=-DZMQ_STATIC

In order to link statically.