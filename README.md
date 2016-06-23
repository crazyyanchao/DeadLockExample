# DeadLockExample
构造两个相互死锁的线程，将进程启动并发生死锁之后，使用jstack观察一下线程的调用栈，确定线程卡住的地方是否与预期相同。
 1.jstack -l 7412
 2.使用JDK给我们的的工具JConsole
