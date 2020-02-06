Building UHD Applications using CMake
=====================================

This directory contains a tiny example of a UHD-based application.
Unlike the other examples, it is completely independent of the UHD
source tree and can be compiled from any path as long as UHD is
currently installed on the current machine.

To try it out, run these commands:
$ mkdir build/ # Creates a new build directory
$ cd build/
$ cmake ..
$ make

This will find the UHD libraries, and link and compile the example
program. Include header directories and library names are automatically
gathered.

See the CMakeLists.txt file to figure out how to set up a build system.