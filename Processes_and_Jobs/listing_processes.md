# Challenge Name
Moving Files

## My solve
**Flag:** `pwn.college{kgVZB2a2BkMQH05_sGOc1EwVqET.QX4MDO0wyM5EzNzEzW}`


```bash
Connected!
hacker@processes~listing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 17:59 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/dojo-workspace/bin/dojo-init /run
root           7       1  0 17:59 ?        00:00:00 /run/dojo/bin/sleep 6h
root         133       1  0 17:59 ?        00:00:00 /challenge/4790-run-31383
root         136     133  0 17:59 ?        00:00:00 sleep 6h
hacker       138       0  0 18:00 pts/0    00:00:00 /nix/store/0nxvi9r5ymdlr2p24rjj9qzyms72zld1-bash-interactive-5.2p37/bin/bash
hacker       144     138  0 18:00 pts/0    00:00:00 /run/dojo/bin/bash --login
hacker       155     144  0 18:04 pts/0    00:00:00 ps -ef
hacker@processes~listing-processes:~$ /challenge/4790-run-31383
Yahaha, you found me! Here is your flag:
pwn.college{kgVZB2a2BkMQH05_sGOc1EwVqET.QX4MDO0wyM5EzNzEzW}
Now I will sleep for a while (so that you could find me with 'ps').

```

## Incorrect tangents I went on
None

## What I learned
I learnt to list all the ongoing processes.

## References 
None
