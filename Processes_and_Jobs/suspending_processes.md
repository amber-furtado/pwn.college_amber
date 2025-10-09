# Challenge Name
Suspending Processes

## My solve
**Flag:** `pwn.college{kPGxcq4_DZZtm0UML-02YkOHVDr.QX1QDO0wyM5EzNzEzW}`


```bash
Connected!                                                                        
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in 
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         161     142  0 18:24 pts/0    00:00:00 bash /challenge/run
root         163     161  0 18:24 pts/0    00:00:00 ps -f

I don't see a second me!

To pass this level, you need to suspend me and launch me again! You can 
background me with Ctrl-Z or, if you're not ready to do that for whatever 
reason, just hit Enter and I'll exit!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in 
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         161     142  0 18:24 pts/0    00:00:00 bash /challenge/run
root         168     142  0 18:25 pts/0    00:00:00 bash /challenge/run
root         170     168  0 18:25 pts/0    00:00:00 ps -f

Yay, I found another version of me! Here is the flag:
pwn.college{kPGxcq4_DZZtm0UML-02YkOHVDr.QX1QDO0wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to suspend a process without killing it. 

## References 
None
