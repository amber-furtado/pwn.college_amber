# Challenge Name


## My solve
**Flag:** `pwn.college{w6hy1rvHs9h6MDjQn-xCufqcDo_.0lMwgDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@chaining~reading-shell-scripts:~$ cat /challenge/run
#!/opt/pwn.college/bash

read GUESS
if [ "$GUESS" == "hack the PLANET" ]
then
	echo "CORRECT! Your flag:"
	cat /flag
else
	echo "Read the /challenge/run file to figure out the correct password!"
fi
hacker@chaining~reading-shell-scripts:~$ echo 'hack the PLANET' | /challenge/run
CORRECT! Your flag:
pwn.college{w6hy1rvHs9h6MDjQn-xCufqcDo_.0lMwgDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to read a shell script.

## References 
None
