# Challenge Name
Finding sessions

## My solve
**Flag:** `pwn.college{4QhLDhZDjYCqJbHFg8YKYw0wKav.01N4IDOxwyM5EzNzEzW}`


```bash
Connected!
schacker@terminal-multiplexing~finding-sessions:~$ screen -ls
There are screens on:
	150.pts-0.terminal-multiplexing~launching-screen	(Remote or dead)
	175.pts-2.terminal-multiplexing~launching-screen	(Remote or dead)
	200.pts-4.terminal-multiplexing~launching-screen	(Remote or dead)
	174.pts-2.terminal-multiplexing~detaching-and-attaching	(Remote or dead)
	209.pts-2.terminal-multiplexing~detaching-and-attaching	(Remote or dead)
	139.pts-0.terminal-multiplexing~detaching-and-attaching	(Remote or dead)
	144.session_3da2e92cd8e5a2ce	(Remote or dead)
	147.session_1843c7abadf271cf	(Remote or dead)
	150.session_3295f53b73ad4464	(Remote or dead)
	144.session_5891a8a6927f978f	(Detached)
	147.session_f83e27784c74e8bf	(Detached)
	150.session_347d56fa86f12400	(Detached)
12 Sockets in /home/hacker/.screen.
hacker@terminal-multiplexing~finding-sessions:~$ screen -r 144
Remove dead screens with 'screen -wipe'.
```
SCREEN 144:
```bash
hacker@terminal-multiplexing~finding-sessions:~$  echo 'Wrong session! Keep looking.'
Wrong session! Keep looking.
```

SCREEN 147:
```bash
hacker@terminal-multiplexing~finding-sessions:~$  echo 'Nothing here! Try another session.'
Nothing here! Try another session.
```

SCREEN 150:
```bash
hacker@terminal-multiplexing~finding-sessions:~$  echo 'Congratulations! You found the right session!'
Congratulations! You found the right session!
hacker@terminal-multiplexing~finding-sessions:~$  echo pwn.college{4QhLDhZDjYCqJbHFg8YKYw0wKav.01N4IDOxwyM5EzNzEzW}
pwn.college{4QhLDhZDjYCqJbHFg8YKYw0wKav.01N4IDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to list all screens and switch between them.

## References 
None
