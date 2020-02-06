UHD test applications using CMake
=================================

## This directory contains tests to be run with the UHD.

´test_clock_synch_b210:´ This program checks the synchronization of two USRPs B210 using Octoclock. 
Modified version of the program test_clock_synch shipped with uhd.
Heavily based on Urban Hakansson code from USRP-users mailing list.

To compile and link this tests with the UHD run:
__$ mkdir build/__ # Creates a new build directory
__$ cd build/__
__$ cmake ..__
__$ make__

This will find the UHD libraries, and link and compile the example
program. Include header directories and library names are automatically
gathered.

See the CMakeLists.txt file to figure out how to set up a build system.

All the CMake configuration used is from EttusResearch uhd github repository.