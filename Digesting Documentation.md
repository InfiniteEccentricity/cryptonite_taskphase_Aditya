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
