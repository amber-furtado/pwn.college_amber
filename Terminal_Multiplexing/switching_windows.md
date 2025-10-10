# Challenge Name
Switching windows

## My solve
**Flag:** `pwn.college{I1bdd6c6pQc6HYfkQ7gI7lqylCy.0FO4IDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@terminal-multiplexing~switching-windows:~$ screen -r

```
WINDOW 1:
```bash
 cat <<MSG
Welcome to the window switching challenge!
You are currently in window 1.
The flag is hidden in window 0.
Use Ctrl-A 0 to switch to window 0!
MSG
hacker@terminal-multiplexing~switching-windows:~$  cat <<MSG
> Welcome to the window switching challenge!
> You are currently in window 1.
> The flag is hidden in window 0.
> Use Ctrl-A 0 to switch to window 0!
> MSG
Welcome to the window switching challenge!
You are currently in window 1.
The flag is hidden in window 0.
Use Ctrl-A 0 to switch to window 0!
```
WINDOW 0:

```bash
hacker@terminal-multiplexing~switching-windows:~$  cat <<MSG
> Excellent work! You found window 0!
> Here is your flag: pwn.college{I1bdd6c6pQc6HYfkQ7gI7lqylCy.0FO4IDOxwyM5EzNzEzW}
> MSG
Excellent work! You found window 0!
Here is your flag: pwn.college{I1bdd6c6pQc6HYfkQ7gI7lqylCy.0FO4IDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to switch windows.

## References 
None
