# Readme
A comparison between Blocking Unix I/O and Non-Blocking Unix I/O.

程序调用阻塞式Unix I/O Syscall之后，内核会让程序保持挂起的状态，等到该I/O操作完成之后，内核会把程序恢复。

程序调用非阻塞式Unix I/O Syscall之后，内核

### Credits
- Computer Systems: A Programmer's Perspective, Third Edition
