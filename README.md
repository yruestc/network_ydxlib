# network_ydxlib
1.核心机制修改自陈硕muduo网络库，ydxlib精简了所有与网络通信无关的代码。用epoller池完成主体工作。
2.加入一个面向字节流的循环队列做网络库和业务程序的缓冲。
3.编写一个多线程安全的收发消息对象Receiver，Sender。
4.修改为Makefile编译方式，生成libydx.so
