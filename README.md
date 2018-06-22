# cmakescripts
A collection of various cmake scripts

FindConfigObj.cmake : A script to check for the presence of the python ConfigObj module. Has version checks

FindH5PY.cmake   : A script to check for H5PY. Has Version checks.

FindMPI4PY.cmake : A script to check for MPI4PY. Has the include path and a version check. Currently we don't use the patch level.

FindNUMPY.cmake  : A script to check for numpy. has the include path and a full version check

FindSCIPY.cmake  : A script to check for scipy. has the include path and a full version check

FindNFFT.cmake   : A script o find the library and include paths of NFFT. Has proper version checks if the nfft version is >= 3.3.0

installviapip.cmake : A script to install pip and then install python packages using pip, e.g. install_via_pip("h5py")

Usage:
Put them in your cmake module include path and then use them:

e.g.:

find_package(scipy 0.9)