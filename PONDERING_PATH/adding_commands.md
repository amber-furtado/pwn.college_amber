# Challenge Name
Adding commands

## My solve
**Flag:** `pwn.college{Urk1HgZBtWamhsLAZIm-nklM_l9.QX2cjM1wyM5EzNzEzW}`


```bash
hacker@path~adding-commands:~$ mkdir ./script
hacker@path~adding-commands:~$ cat > ~/script/win << 'EOF'
> #!/bin/bash
> /bin/cat /flag
> EOF
hacker@path~adding-commands:~$ chmod a+x ~/script/win
hacker@path~adding-commands:~$ PATH=~/script
hacker@path~adding-commands:~$ /challenge/run
Invoking 'win'....
pwn.college{Urk1HgZBtWamhsLAZIm-nklM_l9.QX2cjM1wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to add my own command under PATH.

## References 
None
