# Challenge Name
Scripting with multiple commands

## My solve
**Flag:** `pwn.college{kis4qjAuuMWu9UEA_CaA-Ezb170.0FOzMDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@chaining~scripting-with-multiple-conditions:~$ touch solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ cat > solve.sh << 'EOF'
> #!/bin/bash
> if [ "$1" == "hack" ]
> then
> echo "the planet"
> elif [ "$1" == "pwn" ]
> then
> echo college
> elif [ "$1" == "learn" ]
> then
> echo linux
> else
> echo unknown
> fi
> EOF
hacker@chaining~scripting-with-multiple-conditions:~$ chmod a+x solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ /challenge/run
Correct! Your script properly handles all the conditions with elif.
Here's your flag:
pwn.college{kis4qjAuuMWu9UEA_CaA-Ezb170.0FOzMDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to add multiple conditions using if and elif ladder.

## References 
None
