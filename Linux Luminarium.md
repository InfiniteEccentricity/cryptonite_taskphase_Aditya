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
###### hacker@paths~implicit-relative-path:/challenge$ ./run
###### Correct!!!
###### ./run is a relative path, invoked from the right directory!
###### Here is your flag:
### pwn.college{s-SKVRs5W9TxaKWG60U14G_nkUR.dFTN1QDL5gjN0czW}

## Home Sweet Home
