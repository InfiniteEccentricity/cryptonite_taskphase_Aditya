## The Path Variable
![image](https://github.com/user-attachments/assets/66038282-ee69-4802-8589-abc11a1c45d5)

## Setting PATH
![image](https://github.com/user-attachments/assets/e5404008-3fa3-4f73-bd19-2d6a3e39c86a)

## Adding Commands
Here I first add the command to the win executable, and then I read the PATH variable and copy all the previous directories along with which I add the directory win is in, which allows me to continue using cat while adding win to the path.
![image](https://github.com/user-attachments/assets/851e32b9-bb38-48be-8c37-2b480ce65f43)

## Hijacking Commands
First found the absolute path to the cat command which came out to be /usr/bin/cat, added it to the executable named rm and replaced original PATH variable contents with working directory, which made the program to run rm from /home/hacker which led to cat being called and the flag is seen!
![image](https://github.com/user-attachments/assets/9c42c7a7-f94f-473b-996f-b2b6af3cd88f)
![image](https://github.com/user-attachments/assets/1e45856f-b217-481f-b37e-a03291f7a82b)

