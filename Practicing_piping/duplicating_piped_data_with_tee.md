# Challenge Name
Duplicating piped data with tee

## My solve
**Flag:** `pwn.college{Y_j-bJlKt3yJGEyUPxYr9BbMDKv.QXxITO0wyM5EzNzEzW}`


```bash
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee cmd_output | /challenge/college
Processing...
WARNING: you are overwriting file cmd_output with tee's output...
The input to 'college' does not contain the correct secret code! This code 
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the 
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat cmd_output
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "Y_j-bJlK"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret Y_j-bJlK | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{Y_j-bJlKt3yJGEyUPxYr9BbMDKv.QXxITO0wyM5EzNzEzW}

```

## Incorrect tangents I went on
```bash
Connected!
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code 
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the 
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat pwn
cat: pwn: No such file or directory
```

## What I learned
I learned to use tee to find out what the code should be the input.

## References 
None
