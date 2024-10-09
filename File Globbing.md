# File Globbing
## Matching with *
Here I was prompted to enter 4 characters at max, in the cd command so I used /c* to point to the directory that starts with c which led me to the /challenge directory after which I used the ./r* command to point to the program starting with r (ie. run). <br>

![image](https://github.com/user-attachments/assets/0b78c6e4-9e2a-4101-8127-acec75a04a71)

## Matching with ?
? replaces just one letter and checks other letters that match this pattern.
![image](https://github.com/user-attachments/assets/765ca960-8728-46ef-aba0-b2bc271e4e45)

## Matching with []
cd to /challenge/files and then ran /challenge/ran with argument files_[absh] as [] works like ? but checks for all files from a list of characters.
![image](https://github.com/user-attachments/assets/6dd67fb0-39bd-4aae-b66c-06f0fc5b5145)

## Matching paths with []
Same as the previous questions except this time the argument has to be an absolute path that involves using [] for absh.
![image](https://github.com/user-attachments/assets/57e85731-81cf-4cdf-bf97-0f5db5f1f42e)

## Mixing Globs
In this question we were asked to mix globs, and find the file with p e and c as their starting syllables. So I incorrectly tried to run those files directly but then remembered that earlier we gave arguments to /challenge/run, which worked.
![image](https://github.com/user-attachments/assets/35185f16-5209-487e-8047-26cffcc2b56c)

## Exclusionary Globbing
Excluded pwn using ^ (exclusionary globbing), and adding a * to point the phrase to be matched with if the starting letters are among p, w and n.
![image](https://github.com/user-attachments/assets/4fbd5a7a-8a70-49f6-b5fe-4b87c537d900)

