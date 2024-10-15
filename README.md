# Readme
A comparison between Blocking Programming and Non-Blocking Programming.

为了侦听一个事件是否已经发生，阻塞式编程和非阻塞式编程的做法是不一样的。

阻塞式编程的做法是请求内核把自己挂起，并让内核去侦听那个事件，并让内核在那个事件发生后把自己恢复。

非阻塞式编程的做法是向内核轮询那个事件。
