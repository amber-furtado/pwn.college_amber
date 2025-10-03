# Challenge Name
Sorting data

## My solve
**Flag:** `pwn.college{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxwyM5EzNzEzW}`

When we reverse the order, the last flag becomes the first.

```bash
Connected!                                                                        
hacker@data~sorting-data:~$ sort -r /challenge/flags.txt
pwn.college{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxwyM5EzNzEzW}
pwn.college{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxwyM5EzNzDzW}
pwn.college{UWblbZrPb5t-md0nM-Z3rx1OLCv.0FM0MDNxwyM5EzNzEzW}
pwn.college{UWblbZrPb5t-mc1nM-Z3ry2OLCv.0FM0MDOxwyL5EzNzEzW}
pwn.college{UWblbZrPb5s-md1nM-Z2ry2OLCv.0FM0MDOxwyM5EzNzEzW}
pwn.college{UWblbZrPb5s-md1nM-Z2ry2OKCv.0FM0LDOxwyM5EyNzEzW}
pwn.college{UWblbZqPb5s-md1nM-Z2ry2OLBv.0FM0MDOxwyM5EyNzEzW}
pwn.college{UWblbYrPb5t-md1nM-Z2ry2OLCv.0FM0MDOxwyM5DzNzEyW}
pwn.college{UWblaZrPb5t-md1nM-Z3ry2OLBv.0FM0MDOxwyM5EzNzEzW}
pwn.college{UWblaYrOb5t-ld1nL-Z3ry2OLCv.0FM0MDOxvyM5EzNzEzW}
pwn.college{UWalaZrOb5t-md0mM-Z3rx2OLCv.0EM0MDOxwxL5EzNzEzW}
pwn.college{UVblbZrPb5t-ld1nM-Z3ry2NLCv.0FM0MDOxwyM5EzNzDzW}
pwn.college{UVblbYrPa5s-md1nL-Z3ry2OLCu.0FM0MDOwwyM5EzNzDyV}
pwn.college{UVblaZqPb5t-ld1nM-Z3ry2OLBu.0FM0LDOxwyM5EzNzEzV}
pwn.college{UVbkbZrPb5t-md1nM-Y3qy1OLCv.0FM0MDOxwyM5EzNzEzV}
pwn.college{UValbZqPa4t-lc1nM-Z3ry2OLBv.0FM0MCOwwyL4DzNzEzW}
pwn.college{TWblbYrPb5t-ld1nL-Y3rx2NKCv.0FM0LDOwwxM5EzNyEzW}
pwn.college{TWblaZrPb5t-ld0nM-Z3ry2OKCv.0FM0MDOwvyM5EzNzEyW}
pwn.collegd{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxwyM5EzNzEzW}
pwn.collegd{UWblbZrPb5t-md1nM-Z3ry2OLCv.0EL0MDOxwyL5EzNzEzV}
pwn.collegd{UWalbZqPa5s-mc1nM-Z3rx1OLBv.0EM0LDOwwyM5DyNyEzW}
pwn.collegd{TWalbYrPb5t-mc0nM-Z2qy2OLCv.0EL0MCOxwyM5EzNzEyV}
pwn.collefe{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0LDOxwyM5EyNyEzW}
pwn.collefe{UWbkbZrPb5t-md1nM-Y3ry2OLCv.0EM0LDOxwyM5EzNzEzV}
pwn.collefe{UWakbZrOb5t-md1nL-Z3ry2OKCv.0FM0MDOxwxM5EzNzEzW}
pwn.collefd{UVblbYqPa4t-ld1nL-Z3ry2NLCu.0FM0MDOxwyM5EzMzDzW}
pwn.colldge{UWblbZrOb5s-md1mM-Y3ry2NKCv.0FM0MCNxwyM4EzMzDyW}
pwn.colldge{UWbkbZrOb5t-mc1nL-Z2qy2OLBu.0FM0LDOwvyM5EzNzEzW}
pwn.colldge{UWalbZrPb5t-md1mM-Z2ry2OLCv.0FM0LDOxwyM5EzNzEzW}
pwn.colldfe{UWblbYrOa5s-ld1mM-Z3qy1NLCv.0FL0MCOwwyL5EzNzDzW}
pwn.colkege{UWblbZrPb5t-md1nM-Z2ry2OLCv.0FM0MDOxwxM5EzNzEzW}
pwn.colkege{UWblbYrPb5t-md1mM-Z3ry2OLCv.0FM0MDOxwyL5EzNzDzV}
pwn.colkegd{UWblbZrPb5t-ld1mM-Z2ry2OLCv.0EM0MDOxvxM5DyNzEzW}
pwn.colkegd{UWblbZqOb4t-lc0nM-Z2rx2NLBv.0EM0LCOwvyL4EzNzEzW}
pwn.colkdfe{UWblbZrPa5t-md1nM-Z3ry1NLCu.0FL0LCOxvyM5DyNyEyV}
pwn.coklege{UWblbZrPb5t-md1mM-Z3ry2OKCv.0FL0MCOxwyM5EzNzEzW}
pwn.coklege{UWblbYrPb5t-md1mM-Z3ry2OKCv.0FM0MDOwwyM5EzNzEzW}
pwn.coklege{UWalaZrPb5t-mc1nM-Z3ry2OLCv.0FM0MDOxwyM5EzMzEzW}
pwn.cokldgd{UVblaYrPa5t-md1mM-Z3ry2OKCv.0FL0LCOwwxM5EzMyEyV}
pwn.cokldfe{UWblbYrPb5t-md1nL-Z3ry1OLBv.0FM0MDOxwxM5DzNzEyW}
pwn.cokkegd{TWblbZrPb5t-md1nM-Y2rx2NLCv.0FM0MDNwwxM5EyNzDyV}
pwn.cokkefe{UWblbYrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxvyM5EyNzEzW}
pwn.cnllege{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxwyM5EzNzEzW}
pwn.cnllege{UWbkbYrOb4s-md1nM-Y2ry2OLCv.0EL0MDOxwyM5EzNyEzW}
pwn.cnlkege{UWblaZqPb4t-md0nL-Z2qy2NLCv.0EL0MCOxwyM5EzMyEzW}
pwn.cnkkdfe{UVbkbZrPa5t-ld1mL-Y3rx1OKCv.0FL0MCOxvyM5DyNzEzV}
pwn.bollege{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxwyL5EzNzEzW}
pwn.bollege{TWblbZrPb5t-md0nM-Z3ry2OLBv.0FM0MDOxwyM5EzNzEzV}
pwn.bollege{TWblbYrPa5t-md1nL-Y3ry1NLCu.0FM0MDOxwyL5EzNyEyW}
pwn.bollefe{UValbYrPb4s-mc1mM-Z2ry2OLBv.0EM0LDOwwyM5EyMzEyW}
pwn.boklegd{UWblbZrPb5t-md1nM-Y3qy2OLBu.0FM0MDNxwyL4EyNzEzW}
pwm.college{TWblbYrPb5t-md1nM-Z3ry2OKCu.0FM0LDOxvyM5EzMzEyW}
pwm.college{TValaYrOb4t-ld0nM-Y3ry2OLCv.0FM0MCOwwxM5EzMzEzW}
pwm.colkege{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FL0MDNxwyM5EzNzEzW}
pwm.colkege{UWalbZqPb5t-mc0mM-Z2qy1OKCv.0FM0LDOxwxM4DzNzEzW}
pwm.coklege{UWblbZrPb5t-md0nM-Z3ry2OLCv.0FM0MDOxwyM5EzNzEzW}
pwm.cnllefe{UWblbYqOb4t-ld1nL-Y3ry2OLCu.0EM0MDNwvyM5EzMzEzW}
pwm.bollege{TWblaZrPb5t-md1nM-Z3rx2OKCv.0FM0LCOxwyM5EyNzDzW}
pwm.bolldgd{UWalaZrPa5s-ld1mM-Z3ry2NLCv.0FM0MDNxvxM4DzNzDyV}
pwm.bolkdge{TWblbZrPb4t-md0mM-Z3qy2OKBv.0EM0MDOxvyM5EzNzEzW}
pwm.boklefe{UWbkbZrPa5t-ld1nM-Y2qx2OLCu.0FM0LDOxvyM5EzNzDyW}
pwm.bnlldfe{UWblaYrPb4t-md0nL-Y2ry2NLCv.0EM0LCOxwxL5DzMzEzV}
pwm.bnlldfe{TWblaYrOb5t-ld1nM-Z3qx2OLCv.0EM0MDOxwxL4EyMzEyW}
pwm.bnkkdfd{UWalbZrPa5t-md1nL-Z3rx1NLCv.0EM0LDOxwxL5DyNzDzV}
pvn.colkdge{UValbZrOb5t-ld1nM-Z3ry2OKCv.0FM0LCOwwyM5EzMyDzV}
pvn.cnllege{UVblbZrPb5s-mc1nM-Z2qy2NLCv.0FM0MCOwwyM5EzNzEyV}
pvn.cnllege{TWblbZrPb5s-ld0nM-Z3ry2OLCv.0EM0MDOxwyL5EzNzDzV}
pvn.cnkkege{UWbkbZrPb4s-md0mM-Z3qy1NLCv.0FL0LDOxwxM5EzNzDzV}
pvn.bollege{UVbkbZrPb4t-mc1mM-Y2ry1OKCu.0FM0LDOxvyL4DyNyDzW}
pvn.bollege{TWblbZrPb5t-md1nL-Z3ry2OLCv.0FM0MDOxwyM5EzNzEzW}
pvn.bollegd{UWblaZrPa4s-mc0nL-Z3qy2NLBv.0FM0MDOwvyM4EzNzDzW}
pvn.bolkefe{TWblbZrPb4t-mc1nM-Z3ry2OLBv.0EM0MDOxwxM5EzNzDzW}
pvn.bnllegd{UVbkaZrPb5t-ld1mL-Z3ry1OLBv.0FM0MDNwvyL4EzNzDzW}
pvn.bnkldge{UWalbZrPb4s-md0nM-Z3ry2OLCu.0EL0MCNxvxL4EzMzEyV}
pvm.collefe{UWakbZrPb5t-md0nM-Z2ry2NKCv.0FM0MDOxwxM5EzNzEzW}
pvm.colldge{TWalbYrPb5t-md1nM-Z2qy2NLCv.0FM0MDNxwyM5EyNzEzW}
pvm.cokkefd{UVblaYqPa5s-md1nM-Z3ry2OKCv.0EM0MCOwwyM5EzMyEzW}
own.college{UWblbZrPb5t-md1nM-Z3ry2OLCv.0FM0MDOxwyM5EzNzEzW}
own.college{UVblbZrOb5t-md1nM-Z2ry2NKCv.0FM0MDOxwyM5EzNzEyW}
own.college{TWbkbZrPb5s-ld1nL-Z3qy2OLCu.0FM0MCOxwyM5EzNzEzV}
own.collegd{UVblaZrPb5s-mc1mM-Y3qy2OLCv.0EL0MCNxwyM4EzNzEzV}
own.collefd{UWakaZrPa4s-md1nM-Z3rx2OLCu.0EM0MDNwwxM5EyNzEzW}
own.colldgd{TVakbYrPa5t-md1nM-Z3ry2OLCu.0FL0LDOxwxM5DyNzEyW}
own.colkege{UWblbZqPa5t-mc1mM-Z3ry2OLBv.0FM0MDOwwyL5EzNzDyW}
own.coklege{UWblaZrPb5t-md0mL-Y2qy2OKCv.0FM0MCOxvxL5EyNzEyV}
own.coklefe{UVblaZqOb4s-md1nM-Y2ry2OKCu.0FM0MDOwvxM4EzNzEzV}
own.cokldge{UVakbZrPb5s-md1mM-Y3qy1OLCv.0EM0MCOxvxM4EyMyDzV}
own.cokkdfd{UWblbZqPa5t-lc1nL-Z3ry2OKBv.0EM0MDNxwyM4EzNzEzW}
own.cnklege{TWblbZqPb5t-md1nL-Z2rx2OLCv.0FL0MDNwwyM5DyMzEzW}
own.bollefd{UVakbYrOa4t-md1nM-Z2rx2OKBv.0FL0MDOxwyM5DyMzEzW}
own.boklege{UWbkbZrPa4t-mc1nM-Z2ry2NLBv.0FL0LDOxwyM5EzNzEyV}
own.bokkege{UValaYqPb5s-md1nM-Z3ry1OLBu.0FM0MCNxvyM4EyMzEzW}
owm.college{UVblbZrPb5t-lc0mM-Z3ry2OLCv.0FM0MCOxwxM5EzMyEzW}
owm.colkdge{UWbkbZrOb4t-ld1mL-Z3qy1OLCu.0FM0LDNxwyL5EyNzDzW}
owm.coklege{UWbkbZqOa5t-ld1mL-Z3ry2OLCv.0FM0MDNxvyM5EzNzDzW}
owm.cnllegd{UWblaZqPa4t-md1nM-Z3rx2OKBu.0EM0LDNwvyL4DzNzEzW}
owm.bolldgd{UWblaZqPa5t-md0mM-Z3rx2NLCv.0EL0LDOwwyM5EyMzEzV}
owm.bnkkdgd{UVblbZrPb5t-ld1mM-Z3ry2OKCv.0FL0LCOwvyM5DzNzDyV}
ovn.college{UWalbZrPb5t-ld0mL-Z3ry2OLCu.0FM0LDOxwyM5EzNzEzV}
ovn.colkege{UWblaZrPa5t-mc1nM-Y2qy2NLBv.0EM0MCOxvyM4EzNzEyW}
ovm.bollege{UWalbZrPa4t-mc1nL-Z3ry2OKCv.0EM0MDNxwyM4EzNzEzW}

```

## Incorrect tangents I went on
None

## What I learned
To sort data using the `sort` command.

## References 
None
