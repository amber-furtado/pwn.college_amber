# Challenge Name
Scripting with conditionals

## My solve
**Flag:** `pwn.college{Yuj6TMYulxvH4AOLqnNN4yakAls.0lNzMDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@chaining~scripting-with-conditionals:~$ touch solve.sh
hacker@chaining~scripting-with-conditionals:~$ cat > solve.sh << 'EOF'
> #!bin/bash
> if { "$1" == "pwn" ]
> then
> echo college
> fi
> EOF
hacker@chaining~scripting-with-conditionals:~$ chmod +x /home/hacker/solve.sh
hacker@chaining~scripting-with-conditionals:~$ /challenge/run
Correct! Your script properly handles all the conditions.
Here's your flag:
pwn.college{Yuj6TMYulxvH4AOLqnNN4yakAls.0lNzMDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to use conditionals

## References 
None
