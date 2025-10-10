# Challenge Name
Redirecting script output

## My solve
**Flag:** `pwn.college{8-gphtOo1-OaxtS6kuwyhvGKFzR.QX4ETO0wyM5EzNzEzW}`


```bash
Connected!
hacker@chaining~redirecting-script-output:~$ touch x.sh
hacker@chaining~redirecting-script-output:~$ cat > x.sh << 'EOF'
> /challenge/pwn
> /challenge/college
> EOF
hacker@chaining~redirecting-script-output:~$ bash x.sh | /challenge/solve
Correct! Here is your flag:
pwn.college{8-gphtOo1-OaxtS6kuwyhvGKFzR.QX4ETO0wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to use the | operator.

## References 
None
