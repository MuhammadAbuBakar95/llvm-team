########### LLVM/Specialisation

Directory info:

##### src

This directory would contain the source code for your LLVM passes. Each person should add separate folders under the 'src' directory. 

##### build

The llvm passes are built as shared objects (.so files). These files should be built by your label in the Makefile under the 'build' directory.

##### Makefile

Single project wide Makefile to build your llvm passes. Use separate labels for your passes.

##### docs

Add information about each individual person's update and some documentation about the code written and run instructions.

