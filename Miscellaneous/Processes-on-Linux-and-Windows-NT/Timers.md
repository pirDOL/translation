# [定时器](http://www.tldp.org/LDP/LG/issue23/flower/timers.html)

* Linux

Linux内核记录进程的执行时间和消耗的CPU时间（用户态和内核态）。
进程可以由有自己的定时器，可能以周期运行也可能是单次运行。当定时器到期以后，通常是通过信号通知进程。

* Windows

定时器对象以可执行的支持服务存在，定时器对象会记录流逝的时间，当设定的时间到达或者定时间隔到期以后，定时器对象会释放所有等待的线程（此时这个定时器对象叫做可通知的，signalled）。

