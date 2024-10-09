# Digesting Documentation

## Learning from Documentation
###### hacker@man~learning-from-documentation:~$ /challenge/challenge --giveflag
###### Correct argument! Here is your flag:
###### pwn.college{8z1h_BKZ1jskxQ5cHQn0dCtvRAm.dRjM5QDL5gjN0czW}

## Learning Complex Usage
###### hacker@man~learning-complex-usage:/$ /challenge/challenge --printfile flag
###### Correct argument! Here is the flag file:
###### pwn.college{srEDhgp0mTUGaTK5NKYcsHDUNPr.dVjM5QDL5gjN0czW}

## Reading Manuals
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                                      Challenge Commands                                     CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --suphdf NUM
              print the flag if NUM is 703

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)

###### hacker@man~reading-manuals:~$ /challenge/challenge --suphdf 703
###### Correct usage! Your flag: pwn.college{suRphVd7fx0GDTi3JLLvwctzXpS.dRTM4QDL5gjN0czW}

## Searching Manuals
###### hacker@man~searching-manuals:~$ man challenge
###### /flag
###### hacker@man~searching-manuals:~$ /challenge/challenge --vjtchpv
###### Initializing...
### Correct usage! Your flag: pwn.college{wnUQzyTn2VsbRd-idzz2LWSbRjP.dVTM4QDL5gjN0czW}

## Searching for Manuals
hacker@man~searching-for-manuals:~$ man man <br>
hacker@man~searching-for-manuals:~$ man -k challenge <br>
uozvbxulcd (1)       - print the flag! <br>
hacker@man~searching-for-manuals:~$ man uozvbxulcd <br>
hacker@man~searching-for-manuals:~$ /challenge/challenge --uozvbx 786 <br>
Correct usage! Your flag: pwn.college{Q-uKGo7zDvHQXDbAx86uFOUlPHc.dZTM4QDL5gjN0czW} <br>

## Helpful Programs
hacker@man~helpful-programs:~$ /challenge/challenge -h <br>
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p] <br>

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p <br>
The secret value is: 814 <br>
hacker@man~helpful-programs:~$ /challenge/challenge -g 814 <br>
Correct usage! Your flag: pwn.college{81YdnD_4XTN0CxNDw0dFckNpPYB.ddjM4QDL5gjN0czW} <br>

## Help for Builtins
hacker@man~help-for-builtins:~$ help challenge <br> 
challenge: challenge [--fortune] [--version] [--secret SECRET] <br>
    This builtin command will read you the flag, given the right arguments! <br>

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value <br>
    is "gykA2ZO7". <br>
hacker@man~help-for-builtins:~$ challenge --secret gykA2ZO7 <br>
Correct! Here is your flag! <br>
pwn.college{gykA2ZO74NPnndaYaM4z9I40upU.dRTM5QDL5gjN0czW} <br>
