## Git Basics

Git is cool!

## Unix Shell
<img src="task_unix_shell/shell1.png" width="500" alt="shell1">
<img src="task_unix_shell/shell2.png" width="500" alt="shell2">
<img src="task_unix_shell/shell3.png" width="500" alt="shell3">
<img src="task_unix_shell/shell4.png" width="500" alt="shell4">

Shell is also cool! I will use it a lot in the future when I become web developer.

## Git Collaboration

<img src="task_github/github.png" width="500" alt="github">

I like **_rebase_** command the most! It is the best!

## Memory Management

1. Stack overflow.
2. Will be created anonymous memory mapping instead of using heap memory.
3. Text segment contains code which has been running and Data segment contains 
constant variables initialized by this code. 
```
565140e1c000-565140f20000 r-xp 00000000 08:08 1966087                    /bin/bash
56514111f000-565141123000 r--p 00103000 08:08 1966087                    /bin/bash
565141123000-56514112c000 rw-p 00107000 08:08 1966087                    /bin/bash
56514112c000-565141136000 rw-p 00000000 00:00 0 
5651427fe000-56514281f000 rw-p 00000000 00:00 0                          [heap]
7fa4ff9ef000-7fa500536000 r--p 00000000 08:08 1186484                    /usr/lib/locale/locale-archive
7fa500536000-7fa50071d000 r-xp 00000000 08:08 2495928                    /lib/x86_64-linux-gnu/libc-2.27.so
7fa50071d000-7fa50091d000 ---p 001e7000 08:08 2495928                    /lib/x86_64-linux-gnu/libc-2.27.so
7fa50091d000-7fa500921000 r--p 001e7000 08:08 2495928                    /lib/x86_64-linux-gnu/libc-2.27.so
7fa500921000-7fa500923000 rw-p 001eb000 08:08 2495928                    /lib/x86_64-linux-gnu/libc-2.27.so
7fa500923000-7fa500927000 rw-p 00000000 00:00 0 
7fa500927000-7fa50092a000 r-xp 00000000 08:08 2495951                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fa50092a000-7fa500b29000 ---p 00003000 08:08 2495951                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fa500b29000-7fa500b2a000 r--p 00002000 08:08 2495951                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fa500b2a000-7fa500b2b000 rw-p 00003000 08:08 2495951                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fa500b2b000-7fa500b50000 r-xp 00000000 08:08 2496086                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fa500b50000-7fa500d50000 ---p 00025000 08:08 2496086                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fa500d50000-7fa500d54000 r--p 00025000 08:08 2496086                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fa500d54000-7fa500d55000 rw-p 00029000 08:08 2496086                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fa500d55000-7fa500d7c000 r-xp 00000000 08:08 2495900                    /lib/x86_64-linux-gnu/ld-2.27.so
7fa500f63000-7fa500f68000 rw-p 00000000 00:00 0 
7fa500f75000-7fa500f7c000 r--s 00000000 08:08 1443203                    /usr/lib/x86_64-linux-gnu/gconv/gconv-modules.cache
7fa500f7c000-7fa500f7d000 r--p 00027000 08:08 2495900                    /lib/x86_64-linux-gnu/ld-2.27.so
7fa500f7d000-7fa500f7e000 rw-p 00028000 08:08 2495900                    /lib/x86_64-linux-gnu/ld-2.27.so
7fa500f7e000-7fa500f7f000 rw-p 00000000 00:00 0 
7ffc136e8000-7ffc13709000 rw-p 00000000 00:00 0                          [stack]
7ffc137f3000-7ffc137f6000 r--p 00000000 00:00 0                          [vvar]
7ffc137f6000-7ffc137f7000 r-xp 00000000 00:00 0                          [vdso]
ffffffffff600000-ffffffffff601000 r-xp 00000000 00:00 0                  [vsyscall]
```
Heap - 5651427fe000-56514281f000  
Stack - 7ffc136e8000-7ffc13709000  
MMS - 7fa500536000-7fa50071d000

In this subject everything was new to me and hard to understand. But I think I get some basics.