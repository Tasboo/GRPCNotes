# GRPCNotes
Findings and other things for learning how to GRPC


Install Protobuff compiler and runtime:
https://developers.google.com/protocol-buffers/docs/downloads
 -> https://github.com/protocolbuffers/protobuf/releases/latest
option 1: download source for compiler and runtime and compile yourself
 -> On release page in the links at the bottom: protobuf-all-x.x.x.zip
 -> Follow instructions in Readme.md (haven't done all of that)
option 2: download pre-compiled compiler and runtime
 -> On release page in the links at the bottom: protoc-x.x.x-win64.zip
 -> Extract contents from zip file
 -> Copy extracted contents into a Protoc directory in C:\Users\{user}\AppData\Local
 -> Edit the Path environmental variable to include the following directories:
    -> C:\Users\{user}\AppData\Local\Protoc\bin
    -> C:\Users\{user}\AppData\Local\Protoc\include\google\protobuf
    -> C:\Users\{user}\AppData\Local\Protoc\include\google\protobuf\compiler
 -> To test installation
	1. Open a new command prompt
	2. Type the following: protoc
	3. Press enter
    -> If installation was successful, you shoudl see a list of options for the protoc command
 
