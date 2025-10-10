# Challenge Name
Cracking passwords

## My solve
**Flag:** `pwn.college{wGHF2bfSnTi-eFJoJ6bpqhDfetZ.QX3UDN1wyM5EzNzEzW}`


```bash
Connected!
hacker@users~cracking-passwords:~$ john /challenge/shadow-leak
Created directory: /home/hacker/.john
Loaded 1 password hash (crypt, generic crypt(3) [?/64])
Press 'q' or Ctrl-C to abort, almost any other key for status
0g 0:00:00:15 0% 2/3 0g/s 286.2p/s 286.2c/s 286.2C/s grumpy..keeper
aardvark         (zardus)
1g 0:00:00:20 100% 2/3 0.04943g/s 287.8p/s 287.8c/s 287.8C/s Johnson..buzz
Use the "--show" option to display all of the cracked passwords reliably
Session completed
hacker@users~cracking-passwords:~$ su zardus
Password: 
zardus@users~cracking-passwords:/home/hacker$ /challenge/run
Congratulations, you have become Zardus! Here is your flag:
pwn.college{wGHF2bfSnTi-eFJoJ6bpqhDfetZ.QX3UDN1wyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to leak a password by becoming another user.

## References 
None
