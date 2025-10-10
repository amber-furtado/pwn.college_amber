# Challenge Name
Swicthing windows(tmux)

## My solve
**Flag:** `pwn.college{sMMDnxOP9wjh2khpdn7uIPClQU6.0FM5IDOxwyM5EzNzEzW}`

```bash
hacker@terminal-multiplexing~switching-windows-tmux:~$ tmux ls
challenge_session: 2 windows (created Fri Oct 10 14:59:24 2025)
hacker@terminal-multiplexing~switching-windows-tmux:~$ tmux attach

```

WINDOW 1:
```bash
 cat <<MSG
Welcome to the tmux window switching challenge!
You are currently in window 1.
The flag is hidden in window 0.
Use Ctrl-B 0 to switch to window 0!
MSG
hacker@terminal-multiplexing~switching-windows-tmux:~$  cat <<MSG
> Welcome to the tmux window switching challenge!
> You are currently in window 1.
> The flag is hidden in window 0.
> Use Ctrl-B 0 to switch to window 0!
> MSG
Welcome to the tmux window switching challenge!
You are currently in window 1.
The flag is hidden in window 0.
Use Ctrl-B 0 to switch to window 0!

```

WINDOW 0:
```bash
hacker@terminal-multiplexing~switching-windows-tmux:~$  cat <<MSG
> Excellent work! You found window 0!
> Here is your flag: pwn.college{sMMDnxOP9wjh2khpdn7uIPClQU6.0FM5IDOxwyM5EzNzEzW}
> MSG
Excellent work! You found window 0!
Here is your flag: pwn.college{sMMDnxOP9wjh2khpdn7uIPClQU6.0FM5IDOxwyM5EzNzEzW}


```
## Incorrect tangents I went on
None

## What I learned
I learnt to switch windows in tmux.

## References 
None
