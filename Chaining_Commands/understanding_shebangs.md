# Challenge Name
Understanding shebangs

## My solve
**Flag:** `pwn.college{MN0M3jxF93HySV6j1SRyKBELnLO.0VOzMDOxwyM5EzNzEzW}`


```bash
Connected!
hacker@chaining~understanding-shebangs:~$ touch solve.sh
hacker@chaining~understanding-shebangs:~$ cat > solve.sh << 'EOF'
> #!/bin/bash
> echo "hack the planet"
> EOF
hacker@chaining~understanding-shebangs:~$ chmod a+x solve.sh
hacker@chaining~understanding-shebangs:~$ /challenge/run
Testing your script...
Perfect! Your flag:
Flag: pwn.college{MN0M3jxF93HySV6j1SRyKBELnLO.0VOzMDOxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt that the shell script should begin with a #! (shebang) for the path to the interpreter.

## References 
None
