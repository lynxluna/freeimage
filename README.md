FreeImage QNX Port
===================

This is QNX Port for both Playbook and Blackberry 10 for FreeImage. To build it make sure you already sourced the ```bbndk-env.sh``` from the Blackberry Native SDK. To build the library invoke:

```make -f Makefile.qnx```

There will be three files in the ```Dist``` directory:
- ```FreeImage.h``` The FreeImage Header
- ```libfreeimage-x86.a``` FreeImage static library for Simulator
- ```libfreeimage-armv7.a``` FreeImage static library for Device Target


