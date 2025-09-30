# Challenge Name
Writing to multiple programs

## My solve
**Flag:** `pwn.college{4Vep4MhKDaVW7euyNxHXthnjyZx.QXwgDN1wyM5EzNzEzW}`


```bash
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | >(/challenge/the) >(/challenge/planet)
bash: /dev/fd/63: Permission denied
Are you sure you're properly redirecting input into '/challenge/planet'?
Are you sure you're properly redirecting input into '/challenge/the'?
Congratulations, you have duplicated data into the input of two programs! Here 
is your flag:
pwn.college{4Vep4MhKDaVW7euyNxHXthnjyZx.QXwgDN1wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learned about duplicating data.

## References 
None
