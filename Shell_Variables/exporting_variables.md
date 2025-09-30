# Challenge Name
Exporting variables

## My solve
**Flag:** `pwn.college{40cRqN4WwwS7I8IifYBZvJcci7j.QXyYTN0wyM5EzNzEzW}`


```bash
Connected!
hacker@variables~exporting-variables:~$ PWN=COLLEGE
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ export PWN
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ COLLEGE=PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ /challenge/run PWN
CORRECT!
You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great 
job! Here is your flag:
pwn.college{40cRqN4WwwS7I8IifYBZvJcci7j.QXyYTN0wyM5EzNzEzW}
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!

```

## Incorrect tangents I went on
None

## What I learned
I learnt to export local variables and make them global.

## References 
None
