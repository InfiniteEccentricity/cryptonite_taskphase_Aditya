# Linux Luminarium
## HELLO HACKERS
## Introduction to Commands
###### hacker@hello~intro-to-commands:~$ whoami
###### hacker
###### hacker@hello~intro-to-commands:~$ hello
###### Success! Here is your flag:
### pwn.college{ACVF15asHguBzimsTrk4AJKqqxa.ddjNyUDL5gjN0czW}

## Intro to Arguments
###### hacker@hello~intro-to-arguments:~$ hello hackers
###### Success! Here is your flag:
### pwn.college{8349BjsjSQhxyjhxogvK4UMRhdM.dhjNyUDL5gjN0czW}

## PONDERING PATHS

## The Root
###### hacker@paths~the-root:~$ /pwn
###### BOOM!!!
###### Here is your flag:
### pwn.college{ULDRvX4idMTfWcOdnsYqfII5Zn6.dhzN5QDL5gjN0czW}

## Program and Absolute Paths
###### hacker@paths~program-and-absolute-paths:~$ /challenge/run
###### Correct!!!
###### /challenge/run is an absolute path! Here is your flag:
#### pwn.college{Yx6O9yNUrCGJSBSynACL5Bi5Ofe.dVDN1QDL5gjN0czW}

## Position Elsewhere
###### hacker@paths~position-yet-elsewhere:~$ /challenge/run
###### Incorrect...
###### You are not currently in the /usr/share/build-essential directory.
###### Please use the `cd` utility to change directory appropriately.
###### hacker@paths~position-yet-elsewhere:~$ cd /usr/share/build-essential
###### hacker@paths~position-yet-elsewhere:/usr/share/build-essrial$ /challenge/run
###### Correct!!!
###### /challenge/run is an absolute path, invoked from the right directory!
###### Here is your flag:
### pwn.college{0IKM1Z7BtMpF1Ap8lz_rS-0omZA.dhDN1QDL5gjN0czW}

## Implicit relative paths, from /
###### hacker@paths~implicit-relative-paths-from-:/$ challenge/run
###### Correct!!!
###### challenge/run is a relative path, invoked from the right directory!
###### Here is your flag:
### pwn.college{Aj7g5qHIKBeGWQ7KUP0G0xxWSqB.dlDN1QDL5gjN0czW}

## Explicit relative paths, from /
###### hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
###### Correct!!!
###### ./challenge/run is a relative path, invoked from the right directory!
###### Here is your flag:
### pwn.college{81z5nJ_7CUJXMM_Lo2BVyNycY3G.dBTN1QDL5gjN0czW}

## Implicit relative paths, from /
###### hacker@paths~implicit-relative-path:~$ cd /challenge
###### hacker@paths~implicit-relative-path:/challenge$ ./run nme
###### Correct!!!
###### ./run is a relative path, invoked from the right directory!
###### Here is your flag:
### pwn.college{s-SKVRs5W9TxaKWG60U14G_nkUR.dFTN1QDL5gjN0czW}

## Home Sweet Home
###### hacker@paths~home-sweet-home:~$ /challenge/run ~/a
###### Writing the file to /home/hacker/a!
###### ... and reading it back to you:
### pwn.college{c27W1yGoXR9l7pqhdGsvUI_cu6j.dNzM4QDL5gjN0czW}

# Comprehending Commands

## Cat: not the pet, but the command
###### hacker@commands~listing-files:~$ cd /challenge
###### hacker@commands~listing-files:/challenge$ ls
###### 29444-renamed-run-6910  DESCRIPTION.md
###### hacker@commands~listing-files:/challenge$ ./29444-renamed-run-6910
###### Yahaha, you found me! Here is your flag:
### pwn.college{IzpknL2_ok5r5Tlc3dH_N6mWmTS.dhjM4QDL5gjN0czW}

## Catting absolute paths
###### hacker@commands~catting-absolute-paths:~$ cat /flag
### pwn.college{IJfHpFi3z9g9gURBQ7VihUvHPoZ.dlTM5QDL5gjN0czW}

## More catting practice
###### hacker@commands~more-catting-practice:~$ cd /flag
###### You used 'cd'! In this level, I don't allow you to change the working directory
###### --- you MUST chase pass 'cat' the absolute path of where I put it on the
###### filesystem (which is /usr/share/systemtap/flag).
###### hacker@commands~more-catting-practice:~$ cat /usr/share/systemtap/flag
### pwn.college{kkbqCphJL8L1wRSJ_rZAstLTXRK.dBjM5QDL5gjN0czW}

## grepping for a needle in a haystack
###### hacker@commands~more-catting-practice:~$ cd Desktop
###### You used 'cd'! In this level, I don't allow you to change the working directory
###### --- you MUST chase pass 'cat' the absolute path of where I put it on the
###### filesystem (which is /usr/share/systemtap/flag).
###### hacker@commands~more-catting-practice:~$ grep pwn.college /usr/share/systemtap/flag
### pwn.college{kkbqCphJL8L1wRSJ_rZAstLTXRK.dBjM5QDL5gjN0czW}

## listing files
###### hacker@commands~listing-files:~$ ls /challenge
###### 17596-renamed-run-7590  DESCRIPTION.md
###### hacker@commands~listing-files:~$ /challenge/17596-renamed-run-7590
###### Yahaha, you found me! Here is your flag:
### pwn.college{IzpknL2_ok5r5Tlc3dH_N6mWmTS.dhjM4QDL5gjN0czW}

## touching files
###### hacker@commands~touching-files:~$ touch /tmp/pwn
###### hacker@commands~touching-files:~$ touch /tmp/college
###### hacker@commands~touching-files:~$ /challenge/run
###### Success! Here is your flag:
### pwn.college{EjVpKCoyrFps5HyJfYSQGomn2Wr.dBzM4QDL5gjN0czW}

## removing files
###### hacker@commands~removing-files:~$ rm delete_me
###### hacker@commands~removing-files:~$ /challenge/check
###### Excellent removal. Here is your reward:
### pwn.college{gQrEqNxYdO8ctO_HlhoB634bqKX.dZTOwUDL5gjN0czW}

## hidden files

###### hacker@commands~hidden-files:/$ cd /
###### hacker@commands~hidden-files:/$ ls -a
###### .   .dockerenv             bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
###### ..  .flag-175622468720923  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
###### hacker@commands~hidden-files:/$ cat ./.flag-175622468720923
### pwn.college{Q4psKhb6wicKdc3WH8knH8iUjp5.dBTN4QDL5gjN0czW}

## An Epic Filesystem Quest

###### hacker@commands~an-epic-filesystem-quest:/$ ls
###### SPOILER  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
###### bin      challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
###### hacker@commands~an-epic-filesystem-quest:/$ cat SPOILER
###### Lucky listing!
###### The next clue is in: /usr/lib/x86_64-linux-gnu/perl-base/unicore/lib
###### hacker@commands~an-epic-filesystem-quest:/$ cd /usr/lib/x86_64-linux-gnu/perl-base/unicore/lib
###### hacker@commands~an-epic-filesystem-quest:/usr/lib/x86_64-linux-gnu/perl-base/unicore/lib$ ls
###### Age    BidiM  CI     CWL    Ccc       Dash  Ea   GrBase  Hyphen  In    Jt     NFCQC   Nt      Perl   STerm  UIdeo  XIDC
###### Alpha  Blk    CWCF   CWT    CompEx    Dep   Ext  GrExt   IDC     InPC  Lb     NFDQC   Nv      QMark  Sc     Upper  XIDS
###### Bc     Bpt    CWCM   CWU    DI        Dia   GCB  Hex     IDS     InSC  Lower  NFKCQC  PCM     SB     Scx    Vo
###### BidiC  CE     CWKCF  Cased  DISPATCH  Dt    Gc   Hst     Ideo    Jg    Math   NFKDQC  PatSyn  SD     Term   WB
###### hacker@commands~an-epic-filesystem-quest:/usr/lib/x86_64-linux-gnu/perl-base/unicore/lib$ cat DISPATCH
###### Lucky listing!
###### The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Latin-Modern/NonUnicode
###### hacker@commands~an-epic-filesystem-quest:/usr/lib/x86_64-linux-gnu/perl-base/unicore/lib$ cd /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Latin-Modern/NonUnicode
###### hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Latin-Modern/NonUnicode$
###### hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Latin-Modern/NonUnicode$ ls
###### Regular  TEASER
###### hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Latin-Modern/NonUnicode$ cat TEASER
###### Tubular find!
###### The next clue is in: /usr/share/doc/nmap

###### The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
###### hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Latin-Modern/NonUnicode$ cd /usr/share/doc/nmap
###### hacker@commands~an-epic-filesystem-quest:/usr/share/doc/nmap$ ls
###### 3rd-party-licenses.txt.gz  changelog.Debian.gz  copyright            leet-nmap-ascii-art.txt  nmap_gpgkeys.txt.gz
###### REVELATION                 committers.txt.gz    device-types.txt.gz  nmap.usage.txt.gz        style
###### hacker@commands~an-epic-filesystem-quest:/usr/share/doc/nmap$ cat REVELATION
###### Lucky listing!
###### The next clue is in: /usr/share/racket/pkgs/math-lib/math/private

###### The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
###### hacker@commands~an-epic-filesystem-quest:/usr/share/doc/nmap$ ls
###### 3rd-party-licenses.txt.gz  changelog.Debian.gz  copyright            leet-nmap-ascii-art.txt  nmap_gpgkeys.txt.gz
###### REVELATION                 committers.txt.gz    device-types.txt.gz  nmap.usage.txt.gz        style
###### hacker@commands~an-epic-filesystem-quest:/usr/share/doc/nmap$ cd /usr/share/racket/pkgs/math-lib/math/private
###### hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/math-lib/math/private$ ls
###### array     compiled       flonum           matrix          polynomial        unsafe.rkt  vector
###### base      distributions  functions        number-theory   statistics        utils
###### bigfloat  exception.rkt  inline-sort.rkt  parameters.rkt  syntax-utils.rkt  utils.rkt
###### hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/math-lib/math/private$ ls
###### array     compiled       flonum           matrix          polynomial        unsafe.rkt  vector
###### base      distributions  functions        number-theory   statistics        utils
###### bigfloat  exception.rkt  inline-sort.rkt  parameters.rkt  syntax-utils.rkt  utils.rkt
###### hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/math-lib/math/private$ ls -a
###### .         array     compiled       flonum           matrix          polynomial        unsafe.rkt  vector
###### ..        base      distributions  functions        number-theory   statistics        utils
###### .WHISPER  bigfloat  exception.rkt  inline-sort.rkt  parameters.rkt  syntax-utils.rkt  utils.rkt
###### hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/math-lib/math/private$ cat .WHISPER
###### Tubular find!
###### The next clue is in: /opt/radare2/test/db/perf

###### The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
###### hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/math-lib/math/private$ cd  /opt/radare2/test/db/perf
###### hacker@commands~an-epic-filesystem-quest:/opt/radare2/test/db/perf$ ls -a
###### .  ..  CLUE  cons  dex  dwarf  elf  macho
###### hacker@commands~an-epic-filesystem-quest:/opt/radare2/test/db/perf$ cd CLUE
###### ssh-entrypoint: cd: CLUE: Not a directory
###### hacker@commands~an-epic-filesystem-quest:/opt/radare2/test/db/perf$ cat CLUE
###### Congratulations, you found the clue!
###### The next clue is in: /opt/linux/linux-5.4/include/config/security
###### hacker@commands~an-epic-filesystem-quest:/opt/radare2/test/db/perf$ cd  /opt/linux/linux-5.4/include/config/security
###### hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/security$ ls
###### README  network.h  selinux  selinux.h  writable
###### hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/security$ cat README
###### Congratulations, you found the clue!
###### The next clue is in: /opt/linux/linux-5.4/scripts/coccinelle/api/debugfs

###### Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
###### hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/security$ ls -a
###### .  ..  README  network.h  selinux  selinux.h  writable
###### hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/security$ cat README
###### Congratulations, you found the clue!
###### The next clue is in: /opt/linux/linux-5.4/scripts/coccinelle/api/debugfs

###### Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
###### hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/security$ ls /opt/linux/linux-5.4/scripts/coccinelle/api/debugfs
###### BRIEF-TRAPPED  debugfs_simple_attr.cocci
###### hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/security$ cat /opt/linux/linux-5.4/scripts/coccinelle/api/debugfs/BRIEF-TRAPPED
###### Yahaha, you found me!
###### The next clue is in: /usr/share/locale/pt_PT/LC_MESSAGES
###### hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/config/security$ cd /usr/share/locale/pt_PT/LC_MESSAGES
###### hacker@commands~an-epic-filesystem-quest:/usr/share/locale/pt_PT/LC_MESSAGES$ ls -al
###### total 88
###### drwxr-xr-x 1 root root  4096 Oct  8 18:35 .
###### drwxr-xr-x 1 root root  4096 Sep 15 08:55 ..
###### -rw-r--r-- 1 root root   144 Oct  8 18:35 TIP
###### -rw-r--r-- 1 root root 71769 Apr 23  2020 sphinx.mo
###### hacker@commands~an-epic-filesystem-quest:/usr/share/locale/pt_PT/LC_MESSAGES$ ls -a
###### .  ..  TIP  sphinx.mo
###### hacker@commands~an-epic-filesystem-quest:/usr/share/locale/pt_PT/LC_MESSAGES$ cat TIP
###### CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
###### It is: pwn.college{E7U_9hP0p9Nf21a_b5itjKEHAwd.dljM4QDL5gjN0czW}

