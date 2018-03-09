### 

console.log既不是总是同步的，也不总是异步的。是否为同步取决于链接的是什么流以及操作系统是Windows还是POSIX:

注意: 同步写将会阻塞事件循环直到写完成。 有时可能一瞬间就能写到一个文件，但当系统处于高负载时，管道的接收端可能不会被读取、缓慢的终端或文件系统，因为事件循环被阻塞的足够频繁且足够长的时间，这些可能会给系统性能带来消极的影响。当你向一个交互终端会话写时这可能不是个问题，但当生产日志到进程的输出流时要特别留心。

* 文件(Files): Windows和POSIX平台下都是同步

* 终端(TTYs): 在Windows平台下同步，在POSIX平台下异步

* 管道(Pipes): 在Windows平台下同步，在POSIX平台下异步