# Challenge Name
Fun with group names

## My solve
**Flag:** `pwn.college{E7D-PKdoZtQ-0YD_0NAYRObc2Y4.QXycjM1wyM5EzNzEzW}`


```bash
Connected!
hacker@permissions~fun-with-groups-names:~$ id
uid=1000(hacker) gid=1000(grp19354) groups=1000(grp19354)
hacker@permissions~fun-with-groups-names:~$ chgrp grp19354 /flag
hacker@permissions~fun-with-groups-names:~$ cat /flag
pwn.college{E7D-PKdoZtQ-0YD_0NAYRObc2Y4.QXycjM1wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt about individual groups of all users.

## References 
None
