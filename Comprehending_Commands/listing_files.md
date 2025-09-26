# Challenge Name
Listing files

## My solve
**Flag:** `pwn.college{sRmwLVOVDyOBeQRJTchtPd_jZWl.QX4IDO0wyM5EzNzEzW}`

```bash
hacker@commands~listing-files:/$ /challenge/13325-renamed-run-28302
Yahaha, you found me! Here is your flag:
pwn.college{sRmwLVOVDyOBeQRJTchtPd_jZWl.QX4IDO0wyM5EzNzEzW}
```

## Incorrect tangents I went on
Connected!
hacker@commands~listing-files:~$ ls /challenge
13325-renamed-run-28302  DESCRIPTION.md
hacker@commands~listing-files:~$ cat /challenge/13325-renamed-run-28302
#!/opt/pwn.college/bash

echo "Yahaha, you found me! Here is your flag:"
cat /flag
hacker@commands~listing-files:~$ echo "Yahaha, you found me! Here is your flag:"
Yahaha, you found me! Here is your flag:
hacker@commands~listing-files:~$ cat /flag
cat: /flag: Permission denied

## What I learned
I learned about listing files.

## References 
None
