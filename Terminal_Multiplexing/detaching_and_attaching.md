# Challenge Name
Detaching and attaching

## My solve
**Flag:** `pwn.college{83SBwz-Io7RiwwXlHyBZAVhslHf.0lN4IDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@terminal-multiplexing~detaching-and-attaching:~$ screen
```

```bash
[detached from 139.pts-0.terminal-multiplexing~detaching-and-attaching]
hacker@terminal-multiplexing~detaching-and-attaching:~$ /challenge/run
Found detached screen session: 139.pts-0.terminal-multiplexing~detaching-and-attaching
Sending flag to your screen session...

Flag sent! Now reattach to your screen session with:

  screen -r

You'll find the flag waiting for you there!
hacker@terminal-multiplexing~detaching-and-attaching:~$ screen -r
Remove dead screens with 'screen -wipe'.
```

```bash

hacker@terminal-multiplexing~detaching-and-attaching:~$ echo Yes! Flag is: pwn.college{83SBwz-Io7RiwwXlHyBZAVhslHf.0lN4IDOxwyM5EzNzEzW}
Yes! Flag is: pwn.college{83SBwz-Io7RiwwXlHyBZAVhslHf.0lN4IDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to attach detach then reattach a screen.

## References 
None
