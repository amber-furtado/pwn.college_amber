# Challenge Name
Detaching and attaching (tmux)

## My solve
**Flag:** `pwn.college{cbVf4Hk-sKF8FulbBs1EJaQINgU.0VO4IDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@terminal-multiplexing~detaching-and-attaching-tmux:~$ tmux
[detached (from session 0)]
hacker@terminal-multiplexing~detaching-and-attaching-tmux:~$ /challenge/run
Found detached tmux session: 0
Sending flag to your tmux session...

Flag sent! Now reattach to your tmux session with:
  tmux attach

You'll find the flag waiting for you there!
```

WINDOW:
```bash
hacker@terminal-multiplexing~detaching-and-attaching-tmux:~$  echo Congratulations, here is your flag: pwn.college{cbVf4Hk-sKF8FulbBs1EJaQINgU.0VO4IDOxwyM5EzNzEzW}
Congratulations, here is your flag: pwn.college{cbVf4Hk-sKF8FulbBs1EJaQINgU.0VO4IDOxwyM5EzNzEzW}


```

## Incorrect tangents I went on
None

## What I learned
I learnt about tmux.

## References 
None
