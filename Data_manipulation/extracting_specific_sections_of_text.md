# Challenge Name
Extracting specific sections of text

## My solve
**Flag:** `pwn.college{8OVJIV4IkSDPspSXlPukQ-FbG8T.01NxEzNxwyM5EzNzEzW}`


```bash
Connected!                                                                        
hacker@data~extracting-specific-sections-of-text:~$ /challenge/run
30011 p
2636 w
5094 n
7976 .
7567 c
8010 o
19628 l
15857 l
9315 e
30532 g
15912 e
15241 {
22109 8
12921 O
19558 V
18579 J
14292 I
28673 V
4167 4
13233 I
26137 k
9853 S
1996 D
29995 P
3416 s
15433 p
4068 S
20256 X
25447 l
3143 P
11130 u
24215 k
14226 Q
22880 -
12808 F
20790 b
23251 G
23167 8
18655 T
23650 .
11451 0
19080 1
13458 N
2163 x
26533 E
4761 z
2675 N
6362 x
8318 w
28701 y
10993 M
16302 5
22262 E
18181 z
17929 N
13093 z
27176 E
10205 z
21969 W
13889 }
hacker@data~extracting-specific-sections-of-text:~$ /challenge/run | cut -d " " -f 2 | tr -d "\n"
pwn.college{8OVJIV4IkSDPspSXlPukQ-FbG8T.01NxEzNxwyM5EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
I learnt to display only a specific column of the file.

## References 
None
