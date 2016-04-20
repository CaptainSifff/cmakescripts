# cmakescripts
A collection of various cmake scripts

FindH5PY.cmake   : A script to check for H5PY. Has Version checks.

FindMPI4PY.cmake : A script to check for MPI4PY. Has the include path and a version check. Currently we don't use the patch level.

FindNUMPY.cmake  : A script to check for numpy. has the include path and a full version check

FindSCIPY.cmake  : A script to check for scipy. has the include path and a full version check

Usage:
Put them in your cmake module include path and then use them:

e.g.:

find_package(scipy 0.9)