# Challenge Name
An Epic Filesystem Quest

## My solve
*Flag:* `pwn.college{sKatVgnOpTMjaeRoBEk9IAxJqWI.QX5IDO0wyM5EzNzEzW}`

```bash
Connected!
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
CUE  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin  challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat CUE
Yahaha, you found me!
The next clue is in: /usr/share/pam

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/share/pam
hacker@commands~an-epic-filesystem-quest:/usr/share/pam$ ls
BRIEF                   common-password.md5sums
common-account          common-session
common-account.md5sums  common-session-noninteractive
common-auth             common-session-noninteractive.md5sums
common-auth.md5sums     common-session.md5sums
common-password
hacker@commands~an-epic-filesystem-quest:/usr/share/pam$ cat BRIEF
Lucky listing!
The next clue is in: /usr/lib/ruby/2.7.0/json

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/share/pam$ cd /usr/lib/ruby/2.7.0/json
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ ls
ALERT  add  common.rb  ext.rb  generic_object.rb  version.rb
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ cat ALERT
Congratulations, you found the clue!
The next clue is in: /opt/busybox/busybox-1.33.2/testsuite/wget

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ ls /opt/busybox/busybox-1.33.2/testsuite/wget
NUGGET-TRAPPED        wget-handles-empty-path      wget-supports--P
wget--O-overrides--P  wget-retrieves-google-index
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ cat /opt/busybox/busybox-1.33.2/testsuite/wget/NUGGET-TRAPPED
Yahaha, you found me!
The next clue is in: /usr/lib/python3/dist-packages/sphinx/texinputs_win
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ ls /usr/lib/python3/dist-packages/sphinx/texinputs_win
Makefile_t  TIP
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ cat /usr/lib/python3/dist-packages/sphinx/texinputs_win/TIP
Congratulations, you found the clue!
The next clue is in: /usr/local/lib/python3.8/dist-packages/google/protobuf/compiler

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ ls /usr/local/lib/python3.8/dist-packages/google/protobuf/compiler
LEAD-TRAPPED  __init__.py  __pycache__  plugin_pb2.py
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ cat /usr/local/lib/python3.8/dist-packages/google/protobuf/compiler/LEAD-TRAPPED
Congratulations, you found the clue!
The next clue is in: /opt/linux/linux-5.4/tools/perf/pmu-events/arch/s390/cf_z13
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/json$ cd /opt/linux/linux-5.4/tools/perf/pmu-events/arch/s390/cf_z13
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/perf/pmu-events/arch/s390/cf_z13$ ls
CLUE  basic.json  crypto.json  extended.json  transaction.json
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/perf/pmu-events/arch/s390/cf_z13$ cat CLUE
Congratulations, you found the clue!
The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Shapes

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/tools/perf/pmu-events/arch/s390/cf_z13$ cd /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Shapes
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Shapes$ ls -a
.  ..  .TRACE  Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Shapes$ cat .TRACE
Congratulations, you found the clue!
The next clue is in: /usr/local/lib/python3.8/dist-packages/prompt_toolkit/input/__pycache__

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Shapes$ cd /usr/local/lib/python3.8/dist-packages/prompt_toolkit/input/__pycache__
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/prompt_toolkit/input/__pycache__$ ls
REVELATION                            posix_utils.cpython-38.pyc
__init__.cpython-38.pyc               typeahead.cpython-38.pyc
ansi_escape_sequences.cpython-38.pyc  vt100.cpython-38.pyc
base.cpython-38.pyc                   vt100_parser.cpython-38.pyc
defaults.cpython-38.pyc               win32.cpython-38.pyc
posix_pipe.cpython-38.pyc             win32_pipe.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/prompt_toolkit/input/__pycache__$ cat REVELATION
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{sKatVgnOpTMjaeRoBEk9IAxJqWI.QX5IDO0wyM5EzNzEzW}
```

## Incorrect tangents I went on
None

## What I learned
I learned a lot.

## References 
None
