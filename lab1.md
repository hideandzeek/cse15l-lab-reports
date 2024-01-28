# Lab Report  1 
## Zeke Wang


**Command: cd**
1. no argument:

![Image](cd1.png)

The working directory was /home

There was no output because I didn't specify a directory to change into, hence no action was taken and no output was given. 

2. path to a directory:

![Image](cd2.png)

The working directory was /home

There was no output, but it can be seen that the working directory changed from just /home to a more specific directory that exists in /home, titled /home/lecture1.

3. path to a file:
   
![Image](cd3.png)
The working directory was /home/lecture1

The output gave an error message. This error appeared because the current directory did not have the file, it was in another directory.


**Command: ls**
1. no argument:

![Image](ls1.png)

The working directory was /home

The output listed the names of the files in the current directory, which was lecture1. 

2. path to a directory:
   
![Image](ls2.png)

The working directory was /home

The output listed the names of the files in the specified directory, which contained Hello.class, Hello.java, messages, and the README file. 

3. path to a file:
   
![Image](ls3.png)

The working directory was /home

The output was an error message. The error occurred because the current working directory was /home and I didn't have access to the file. The file that I used for the list command was in another, more specific directory called /home/lecture1/.

**Command: cat**
1. no argument:
   
![Image](cat1.png)

The working directory was /home

I did not specify a directory for the concatenate command. There was no output, and the cat command made the terminal a keyboard that prints anything that I typed out. 

2. path to a directory:
   
![Image](cat2.png)

The working directory was /home

The output printed information about the specific directory. Because the directory had multiple files it didn't print any content of the directory. 

3. path to a file:
   
![Image](cat3.png)

The working directory was /home

This gave an error output. The error occurred because this working directory does not have access to the file its trying to concatenate.
