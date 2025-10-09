# Challenge Name
Killing misbehaving processes

## My solve
**Flag:** `pwn.college{YN2C-bItCSUIXapYmGxfpbhYM_O.0FNzMDOxwyM5EzNzEzW}`

SSH:
```bash
Connected!                                                                        
hacker@processes~killing-misbehaving-processes:~$ ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.2  0.0   1056   640 ?        Ss   18:18   0:00 /sbin/docker-init -- /nix/var/nix/profiles/dojo-workspace/bin
root           7  0.1  0.0 231708  2560 ?        S    18:18   0:00 /run/dojo/bin/sleep 6h
root         137  0.0  0.0   4132  1280 ?        S    18:18   0:00 /bin/bash /challenge/.init
root         138  0.0  0.0   4132  1280 ?        S    18:18   0:00 /bin/bash /challenge/.init
root         139  0.0  0.0   5204  3520 ?        S    18:18   0:00 su -c exec /challenge/decoy > /tmp/flag_fifo hacker
root         140  0.0  0.0   2744  1600 ?        S    18:18   0:00 sleep 6h
root         141  0.0  0.0   2744  1280 ?        S    18:18   0:00 sleep 6h
hacker       142  0.2  0.0  13516  9280 ?        Ss   18:18   0:00 /usr/bin/python /challenge/decoy
hacker       144  0.2  0.0 231576  3200 pts/0    Ss   18:18   0:00 /nix/store/0nxvi9r5ymdlr2p24rjj9qzyms72zld1-bash-interactive-
hacker       150  0.0  0.0 231972  4160 pts/0    S    18:18   0:00 /run/dojo/bin/bash --login
hacker       168  0.1  0.0  36972 21760 ?        S    18:18   0:00 /nix/store/g0q8n7xfjp7znj41hcgrq893a9m0i474-ttyd-1.7.7/bin/tt
hacker       182  0.0  0.0 233600  3840 pts/0    R+   18:18   0:00 ps aux
hacker@processes~killing-misbehaving-processes:~$ kill 142
hacker@processes~killing-misbehaving-processes:~$ /challenge/run
Sending the flag to /tmp/flag_fifo!

```

Terminal: (last one is the correct flag)
```bash
hacker@processes~killing-misbehaving-processes:~$ cat /tmp/flag_fifo
pwn.college{o1PWrs3rQvQgRs1POIBAKdSHlEh.oiGOv-uSrwbTfag4EmL}
pwn.college{R2tBVLohq1-gLBMH6izVs4ir1TFEsdpqW2uw1YsVMKdb3vV}
pwn.college{QbbeUhnVA3tlmRAFIx0e.ZbsUiK.6xFZGhm6RSThjJTLNvX}
pwn.college{JaRU3xQcZUDITdw36pJiLSOAPqDngYKEvi30dZnO8Y5XadK}
pwn.college{thwGgw5dcgeiQU3kgKS9p9w76Z0.q3NeRdFOIz-xrOEDwEf}
pwn.college{Ahwexz0b3Fr72IZX6BBlqzhP6331LCPa-Ey0NAkuUy9c5.o}
pwn.college{9iF9.BP8gTNm-z5Idwn2f9gJ.w6rbKCTGqVFVC2Uaebh8UN}
pwn.college{c1CiJaJdtvHxmccZ3QeJ28LreHUF.C3yk4VkpqaiL96fSYl}
pwn.college{yb.5L-6bffaMqt-MY-hu2y5.Fc02MGFZ8.wks4ATmFwnop8}
pwn.college{m-Yy0uUAwA-i3N8O7UgwVSmwzOVMzY91XwkghXztGjx1vCd}
pwn.college{9FxHeYwtI.RJVWsEx6EJdWr4g7FNG1P0XU.4lpt1XOvnOnl}
pwn.college{kZ2dXoh3YECxwyJxAm3LNpUKbpnxqKkqcIhz-0Pc2BJY83i}
pwn.college{3oFOVLlR4islRYbZW09e1M6P9Y8bWhW9SiXMSTPtiwmmua2}
pwn.college{Zr9PHffuV0rY4jUufQRMIt2LVEYpIWN7A2unRzIyY3Fzv0t}
pwn.college{mO87rfPFnacErgurtTs8mY4uhHylDw4I8vg4tOLG3IaQ9.6}
pwn.college{3YKh7.iqQfbKKwFVv5iPEM2c.osHgNYeG0HmAF6dwUW28Mg}
pwn.college{rGZwZiqa2aFH2EKOeftYPzsYFWeSTh8kvsW9uCCTU6Ula77}
pwn.college{oFwnXpJBB-bsKOyYNAc6BKY.HvTp.c69wirTdlEqobhl6ut}
pwn.college{iJEutwDefb0HchIqaagtEwnRVAwRGyJ34aLGOOcWGiHonF0}
pwn.college{e4Qr3hWvlZQVq.KLZrbhUO2aPjl0yvH5k8ybqxLjNU77REM}
pwn.college{4q6JLekAPIqcZP9Woad1mEv-3Wy8sRNeBDW2rrKtDC9Qx8P}
pwn.college{efkva-z6SQAwZov8LAXkt33RaKZDTqW-G-XPV-DJJbvByL.}
pwn.college{S-56G-nQpT.uSgZZ6d7D6AmXr1DZVIds7SCremUCI8eMh8s}
pwn.college{xzNEHd68fo3-L-x2sl76JwdC9Kf075qMxam0mD0uqcifav8}
pwn.college{Y1ldKZR1-4T7gZzIOndc19WCx4BlgzAp7imrFYPDyffRYzK}
pwn.college{2jQEp4o6Ui9hG729muIH1IW7gag1.rp3nocTgqNdm-m1J0Y}
pwn.college{yXoAgyosG0LoGw0t2kaQe7J62I0eHtgbGxNWzoiQPyTv2hG}
pwn.college{8cMOK3tTNQRdOpVWQd--DlAyE9hteeYNsGRkEeOew32Mfrq}
pwn.college{jnL6zDsvoBG3WB7HFuZGD1MmIRPxa-Emof2ChAlrTqmD.F3}
pwn.college{8YFdRk9FzVcwP.pDsiGFslzEZYDqpVsOUXf7ZbvYYTvYQGc}
pwn.college{EJdo0mjWJOGxPWheUapQaY.Mog-XIQdY08VJU6Hd1JqYbad}
pwn.college{DU8bhoputNgiONoBCdtXi2IoQHWH.5jOVUXonykwks4Jf4x}
pwn.college{ru6xf.UYy-BPH.6wO7Y2cgrt09kVpMSeuLgDDtChHb8K-Lr}
pwn.college{yDleyJtwv5U0bxB0xwJ4UWVKrcoxztQmgcLB4P0Apk8BMvQ}
pwn.college{e4-mEA91ZV3UbdFzh0vO-WMXvWQ3ptX-TcrvYM3h.LUQ.hm}
pwn.college{yYvIAZrbE4Zsb1mDGCNdz6-OSHG9k8dvyCA4odxBMa460DY}
pwn.college{isymgr85B9.hy86wRKTT59UMSlzadCIuZHIIbt9l4QuOmIT}
pwn.college{rlCb3c5hIutt.C9KoU8uxb84o2sjcZ3k.zBYOoCRTEkb.mL}
pwn.college{wEs-3oq.y6qHLrA67F.YQVjcoOBRtzcWkumdy4g3amI7Nhi}
pwn.college{h2gt-OuFQTyJoNMH5Xbx7qtiw3DQmWMheRbVDqB9kxOXlVp}
pwn.college{6xCQVinpwZD.nN1q1ADG3z68DuIXoZeL3ZOOuNR95LRopgj}
pwn.college{9Mpk6hVFaLPxU6dWy7YnNIn1gGDipo33XFUG4mq1RFeO6IS}
pwn.college{534-qY0TgbnO6LxPlcd5Hea2j6jrDaqR8z1Au9PS7RKUwzp}
pwn.college{IczNTKweeQpD4Oe7H.mYP0B-uQhHYfF49ST1c16vdfBcsg-}
pwn.college{ceVeHrkONFlH0xEGAG4O2NTYc9HFjEm8USFUc8Zved-EHrC}
pwn.college{VTFv8R.-l.cU0Q0EsNex4qSDmLYCJc1nJxPo9cDGfm2IJ4o}
pwn.college{6ft3IqizPCZu1hCTZ92oxj58gxcNvxUSb13wD6aFMWVsPBM}
pwn.college{h0dSzckVUwUd8a2SJ2tVQDcrpQKpyHxBK1Bt8L0.I5mIykq}
pwn.college{uhK6.fqq1lvkzrUBdU0Emy85VMZ1uIeB1PMaxSLyYD8LV3v}
pwn.college{HhK0OAV-NC73HVN9rm.aJQZPg4mH5jf.HAFaiMFPrn7PY16}
pwn.college{yUSvjtANnrz8H9YXNWw6tk3TbljXLVoJASH24lnFWAX1Bfd}
pwn.college{81kIh6F5i0bvLnrdHzjXi-3YsxxtZCv-Q4ixIDktdJevRng}
pwn.college{S6ttbug91ZhS1hDQJgi29Nhgc2dpMIfZIlEwqstMrmLnShP}
pwn.college{DL.GIUL-38UMopQg.VasZyMhqEVpoBmzXPVEvjldYLYjOSS}
pwn.college{0tMwMPWo5-RLdlShDZnxcVWyLlJuntCZgZw6DbLHoR4EDcf}
pwn.college{Y-MJMcl5uGnWTuXyRQLZ0MXBVWqQ7vOdPYGRrFjRWTtCwW3}
pwn.college{e5-ihjYAk8GqmfxDApjaYungTOP0vBCWKULoEekO3fqOplH}
pwn.college{LrjnlXV5Zc1lkUWDwTGsddWVojT2eCI4SniAba1Jv255l1K}
pwn.college{PRXRftpJBFU.gageLgFUal3mrU0aO3rE9yUGz0IJZs7qbFb}
pwn.college{DhWQa-qbYWa64i.OGDFmXQyNQAPxi9cc99VDF4Ac5qfOgrL}
pwn.college{OSQNMVHYQ6u9EB8jaGyKg4CoRW56Rx2OOSKFBWFbbrKSr7M}
pwn.college{-IKf5oaGSfDu9c-imo8ESOiaj30Vv2Xhui4.nBCNdKjF2Jp}
pwn.college{R3t1-XOl351cInMvPmrKre8ctkqMl2YM8qdkHfDVvIwFc8c}
pwn.college{yHyExZB-ZxkL2cXQlZRAFIKtL9nddse48HvONE5vtCBD1m1}
pwn.college{KNuI4WI6AyY9ZlRRe5n.ZGK1wb3QQzQS7QooYMzpM55Dzim}
pwn.college{3l8bJXTEx8iWLx7A8xbQQcZnlc0cPOCaQMHP47SF.-D95Tn}
pwn.college{oZ4ui0dfCWzKh96PTWdJ6Or0MfgLXxgSnG9QScOXEhIUcwV}
pwn.college{rRVMK4XO66s9WusfgBSCdlyJXvjtYqFa.k6NYAkGXaNpd1W}
pwn.college{vHkIHIdLK36nIDs-8Z1l.1S9S.0VACszGQyj4oEgxqhKzRK}
pwn.college{tciCQzxBhjVLfwc2F77nJkmyCD8Piz21mPoifpbjJ8mkb55}
pwn.college{7KXU78rkqM0w4RKUulMrNFbregLWMn0VMWR2rjlM0wydvCE}
pwn.college{NaANI1GjxfqGU2QprXWQz1yb4gxtWfQinDGCjazMBrV1frn}
pwn.college{EgsglDJbARJ-ozHBLjZp7lhXUTGzngIr4q0X0fJhlWvlWga}
pwn.college{KqPOP2R1aSd-Lt0iFDOPQH1fQqzueZsoCXg4PBDhEurUyqD}
pwn.college{Fz5bx3mLAgyhAbvEuYky.i-NsiJfY2OjWnU5NPpRnBgD2.a}
pwn.college{YwQNQn5Rvgj2WjQwtBooFVbzegIMTegJP2UXkCrFrlo8ZcK}
pwn.college{1jleV6GQ52Vj7OvMq3Jg8M.eZCIH-50Lxe4mXr6GHByFjmX}
pwn.college{PBmY22AmcC8dmqf9Ojd3Cp74qdejfPfH0MYZeEin3s9fvu4}
pwn.college{CT7d3X2SdIsYT27S.VUFC4nvoBCzKTQr15Db75BHbuGjW7X}
pwn.college{IvZ7Hl7vcSc7CYcI.hadut6pnUKaD2jkIybw-yu41fRtHH0}
pwn.college{ZzEkFJvJhySKZtn0kT5.IPwJ4w2ZOLHAqRnbzVrrXDssW8z}
pwn.college{K4fdI7e-UOUqnKyW87zuI8Mey0XBK1jk9xF3hVAyHkSvPcu}
pwn.college{QLaBN16IE3Pnqllm0DkeNQx-nJWtBBoIltj0Z4LAHYLana-}
pwn.college{fLc9DNxeGVcZJFHhWPGIIuX8qiNvXXC9x77OzrKurezpG1y}
pwn.college{Uz0U3YSDgAnyjA.11AC1DDlssOjxlGuDzo.4ezUnQkJ.wAk}
pwn.college{CC.jrBWFgk4zzbRyBPoDI0cXp5MnYJon2BQ67JFRUrfvbNH}
pwn.college{Q64bhQ1m3AT0QKvDdEO3z9hNTJ0S7LZ3c0q9Yh7s.uG5Q1P}
pwn.college{mhegNebkXQg6K4uGg6LQziPx4KCf9Qk5a7ivat7Wac0WOzX}
pwn.college{lfeqvsjjKEj.ZW2FOEn3XJ4ZEDL0aUz9glklnKtf37tqJSK}
pwn.college{z9DDaDFVPcMHtRcHiKfHFWnnUKHXTxgweLP6IS0MS4WX0xm}
pwn.college{KoWXEd0wX1GR7O4788DXIjGXIdxZ0TlBuip1IQUFyybsiFb}
pwn.college{3UALTZbrTZi8PXyGt4qqpvdeMt.-KSAA-f0cvDHLQbl0-cU}
pwn.college{cN1zLsTuEIFGIVNNg3auxeMYChIfE0UFwXY0PDGdEVnkZgY}
pwn.college{ptr1CHnkHIDZ7l2n231UU10sbVn7ZyMZPqGoF3lAKKdJvpm}
pwn.college{s-3bRDIkvIxUVOLKC8sp3Qwv-jXz2UsJJ0yXPwqYB5axI9H}
pwn.college{ryKrfQVnJzM.dfQHCwQlvsEaQOzmbMEZJO5NPemu8vMe6il}
pwn.college{gv-f11Ct-CJlayRMkRTMMvzjG1KLmZC6vJDpoQfsDJ39ovw}
pwn.college{T8GZGPXUBX3vuP-67VVjjPxayytgeOzeuI2-8a-zUazLLZA}
pwn.college{zM9gFZR7s0-P456RBVKzrxUtuQqHsyT3pTOddmRfF3HpGxa}
pwn.college{pGTbE-Bo3f.8N2OhsXkPzuW7aUamTcJvqC5.E31aFvThucz}
pwn.college{SHVj02QZSNfmDGpnsh0i.Vf.-xU9oUm2sPvdMCfPahJf-Cb}
pwn.college{vbyefPkKUOzT5YKK.oNG4R9IMFnyzUiyA1w2mROS3B1eRnN}
pwn.college{ZSSdggT8-blGJ-MyHIPIpdQ7CahVbxyQRs1rBz5HojndrN.}
pwn.college{mkqJPZM7aByqaYrpxzhjIPAf.HqaXD7pPP7vboMb.f15zx7}
pwn.college{f3BUZVIji8.HAZgJoM8JvrT47iYIVGBSJpTNlBaZNVaI82P}
pwn.college{fjJGbpo7vfvbQ02T.UcNFHayqX3vH7zWwlw6lG2011n4GLv}
pwn.college{KbRayEy79kOfoHVqQaOZDaTENI8DsvrnWjuIIs9YnOZ-U7V}
pwn.college{9oyc4YSssfGAvWgQFHrlupGk23v8f2K3tb-teFWezADJ7wD}
pwn.college{NWUDaB.bRhJbm2fzoizAE5K.alrhjo8fu-JeaZEJQWT-yv5}
pwn.college{ntGnbBWycwRdt0tvY0aPrTRbLInNByfB2YGRHmjthILEyqi}
pwn.college{lyLnBJmdE6Uy8f4BFte.SOdxWihN2XqlqgUE-3AkcJwl4xF}
pwn.college{w79ZPBMQywWm6..q1MffSOcWdr3IJNpobSe7HSeBkPaFCvM}
pwn.college{QcUhEuBdfBT5yKkjlZahJsJiHxozLBl3JzmuV2mQzN.WDQl}
pwn.college{msKR9dS7G1VG.4vVAvZCMCW7Lo2Kfw-s1mCyd1or6psVPCk}
pwn.college{g7i0da90xXmM85Fv41070VvW0XmCIRxSs0kCTW38NUOr63s}
pwn.college{wpnQbGzZbiHtFygp2X-2I6tlAMYJT4V3XoZx32QVnbYzJWT}
pwn.college{sNoFIzIqDPNY.RtQdYrUmHXv3vnkkuoZwZtPSVUD0fs9Ncb}
pwn.college{VPImjCnztIujF2w7WljuzM0LalmOhJLAusREX8W.KrvagQA}
pwn.college{G0BqvcPRtEKEZ59eddtkLAGzT-AyvD5EWHw9JaQc1wqvjls}
pwn.college{GmPEhySb7wleKeP7YmZEwz9D4fIMUrveH9unSLMbB7eorop}
pwn.college{4NOhh3BG68mgS0cOwBIc7GJ.6nDvPLW9luJGk73Ykmg0HU4}
pwn.college{luXQV0neI3y1OqTuvrBj3vwbsPHwvl2AmyHSI9Jyv.vVliI}
pwn.college{.ABRqyBn3S7oqytFYWGtXTptAcFEGoJVTUsOuyWMqPMMTPR}
pwn.college{VD1JmbSNcyZXBrhwpRCA70Ba0bSbwxJ3MonfmxUxXarPlJE}
pwn.college{mtaTbSYAToblaODCAgB5R1KWrKUZxFYm1LkaUGO-zzQAdiD}
pwn.college{hm3yJ07l9KjEOoBGmO999qRYpPVUUUv2z9rEN4qeFJtj9e2}
pwn.college{8n3BOo3N4ZxueLPQhqUFEuZcYJX-oe.lkG-2ueDjK9kcCJO}
pwn.college{uJwsvV5H2.7FodiD7ec1Kb8MXwDXrfk02KkuIrfI50VDASS}
pwn.college{j6eqAJ6pEvwwPRvlYjQI4mT3ap-xB23Yx3YtJhk6FyXRCxS}
pwn.college{1Ii92HKfc2i4iyP2j5cUlKdWD81UoB2ZSi-.laulT.iemMz}
pwn.college{ajTvp8E3hQpmaqmn4mSKcoZpka4nttBnxA6YiMruNO5jhAT}
pwn.college{MaDZuQt7QWpREY0bz7UyPanKirk0umw6NyfqUtvdimqyjIQ}
pwn.college{0mHSJjsGTQDdwA5ERuBnMl1QWPIC23GXkp1Mii7tkeCgtdY}
pwn.college{9830spuanBoSmzp1RIt2XZ0QFEEJxo3YGPNGIqgqtctlPgI}
pwn.college{YN2C-bItCSUIXapYmGxfpbhYM_O.0FNzMDOxwyM5EzNzEzW}
```

## Incorrect tangents I went on
None

## What I learned


## References 
None
