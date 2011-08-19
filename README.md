# libSOIL for Mac OS X
This is libSOIL (Simple OpenGL Image Library) with modifications to the Makefile to let it install nicely on Mac OS X. By default, libSOIL.a and libSOIL.dylib will be installed in /opt/local/lib/, and the libSOIL headers will be installed in /opt/local/include/SOIL/.

# Installing
Clone this repo, make, make install. To install elsewhere, change the INCLUDEDIR and LIBDIR in the Makefile. If you do this, be aware that the install\_name for libSOIL.dylib must be the same as full absolute path to that file, or else any programs linked against it will fail to load.

# License
Public domain.

