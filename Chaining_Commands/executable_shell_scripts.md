# Challenge Name
Executable shell scripts

## My solve
**Flag:** `pwn.college{gqnrKfo_f7hcZtN9F7uRECDZxvA.QX0cjM1wyM5EzNzEzW`


```bash
Connected!
hacker@chaining~executable-shell-scripts:~$ touch x.sh
hacker@chaining~executable-shell-scripts:~$ cat > x.sh << 'EOF'
> /challenge/solve
> EOF
hacker@chaining~executable-shell-scripts:~$ chmod +x x.sh
hacker@chaining~executable-shell-scripts:~$ ./x.sh
Congratulations on your shell script execution! Your flag:
pwn.college{gqnrKfo_f7hcZtN9F7uRECDZxvA.QX0cjM1wyM5EzNzEzW

```

## Incorrect tangents I went on
None

## What I learned
I learnt to make an executable shell script without using bash.

## References 
None
