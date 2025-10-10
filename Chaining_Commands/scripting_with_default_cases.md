# Challenge Name
Scripting with default cases

## My solve
**Flag:** `pwn.college{wMcdGNN1M-K-QmvAOsuxU5FF7j9.01NzMDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@chaining~scripting-with-default-cases:~$ touch solve.sh
hacker@chaining~scripting-with-default-cases:~$ cat > solve.sh << 'EOF'
> #!/bin/bash
> if [ "$1" == "pwn" ]
> then
> echo college
> else
> echo nope
> fi
> EOF
hacker@chaining~scripting-with-default-cases:~$ chmod a+x solve.sh
hacker@chaining~scripting-with-default-cases:~$ /challenge/run
Correct! Your script properly handles the if/else conditions.
Here's your flag:
pwn.college{wMcdGNN1M-K-QmvAOsuxU5FF7j9.01NzMDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to use if else with fi.

## References 
None
