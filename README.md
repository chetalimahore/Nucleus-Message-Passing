# Nucleus-Message-Passing
Interprocess Communication using Nachos in C++

Idea:
The purpose of the system nucleus is to implement these fundamental concepts: simulation of processes; communication among processes; creation, control, and removal of
processes.

Description:
Nucleus(Kernel of OS) is the core of communication between different processes. The process communication takes place via messages and nucleus facilitates this communication.

Implementation:
Implemented system calls to handle the multiple messages sent by various processes. The system calls are defined in exceptionHandler.cc.
Declared the data structures at the global level(i.e kernel level) in kernel.h file to manage the communication. 
Made changes in addrspace.cc to handle the contiguous allocation of memory to processes. 
Added new files i.e. buffer.h and buffer.cc for defining message structure.

