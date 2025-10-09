# Challenge Name
Killing Processes

## My solve
**Flag:** `pwn.college{IDGz7_sWpo-8dJUdM9CvT6d8o8C.QXyQDO0wyM5EzNzEzW}`


```bash
Connected!                                                                        
hacker@processes~killing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 18:08 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/dojo-workspace/bin/dojo-init /run
root           7       1  0 18:08 ?        00:00:00 /run/dojo/bin/sleep 6h
root         135       1  0 18:08 ?        00:00:00 su -c /challenge/.launcher hacker
hacker       136     135  0 18:08 ?        00:00:00 /challenge/dont_run
hacker       137     136  0 18:08 ?        00:00:00 sleep 6h
hacker       139       0  0 18:08 pts/0    00:00:00 /nix/store/0nxvi9r5ymdlr2p24rjj9qzyms72zld1-bash-interactive-5.2p37/bin/bash
hacker       145     139  0 18:08 pts/0    00:00:00 /run/dojo/bin/bash --login
hacker       154     145  0 18:09 pts/0    00:00:00 ps -ef
hacker@processes~killing-processes:~$ kill 136
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{IDGz7_sWpo-8dJUdM9CvT6d8o8C.QXyQDO0wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learned to kill an ongoing process.

## References 
None
