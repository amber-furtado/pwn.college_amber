# Challenge Name
Deleting characters

## My solve
**Flag:** `pwn.college{EpwqDfx0ZA1-e_YyBSRcHq_Gzzy.0FNxEzNxwyM5EzNzEzW}`


```bash
Connected!
hacker@data~deleting-characters:~$ /challenge/run
Your character-stuffed flag:
pw%n^%.c^%o^%ll^%e^%g^e%{^%E^pwqD%f^%x%0^Z%A^%1^%-^%e_^Y%y^%BS^%R^cH^%q%_^G%z^z^y.^0^%F%N^x^%E%z^%N^x^%w%y^M^%5^%E^%z^%N^z^E^%z^W%}
hacker@data~deleting-characters:~$ echo pw%n^%.c^%o^%ll^%e^%g^e%{^%E^pwqD%f^%x%0^Z%A^%1^%-^%e_^Y%y^%BS^%R^cH^%q%_^G%z^z^y.^0^%F%N^x^%E%z^%N^x^%w%y^M^%5^%E^%z^%N^z^E^%z^W%} | tr -d ^%
pwn.college{EpwqDfx0ZA1-e_YyBSRcHq_Gzzy.0FNxEzNxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to delete characters using the -d flag along with the translate command.

## References 
None
