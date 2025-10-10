# Challenge Name
Scripting with arguments

## My solve
**Flag:** `pwn.college{of4klSLgIjpJh5TCXPsa5uhmLLZ.0VNzMDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@chaining~scripting-with-arguments:~$ touch solve.sh
hacker@chaining~scripting-with-arguments:~$ cat > solve.sh << 'EOF'
> #!/bin/bash
> echo "$2 $1"
> EOF
hacker@chaining~scripting-with-arguments:~$ /challenge/run
Correct! Your script properly reversed the arguments.
Here's your flag:
pwn.college{of4klSLgIjpJh5TCXPsa5uhmLLZ.0VNzMDOxwyM5EzNzEzW}


```

## Incorrect tangents I went on
None

## What I learned
I learnt to include arguments in the shell script.

## References 
None
