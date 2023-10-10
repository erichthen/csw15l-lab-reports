# Erich Then - CSE15l Lab Report 1
# CD COMMAND  

## No argument command and output: 
**No output, command:[user@sahara ~]$ cd**  
**Working Directory:** /home
**Explanation:** I believe the output is blank because cd is used to move between directories,
but it needs the argument of where to go to. 
**Error?** I wouldn't call it an error because it is blank. It moved back to the home directory.

## Directory as an argument command and output: 
**No output, command: [user@sahara ~]$ cd lecture1**  
**Working Directory:** /home/lecture1
**Explanation:** This output or lack thereof means that the command worked and the one visible change
was the prompt now containing lecture1: [user@sahara ~/lecture1]$
**Error?** Not an error

## File as an argument command and output  
![](cd_file.png)
**Working Directory:** /home/lecture1
**Explanation:** I believe this is because the cd command is
looking for a directory to switch to, and not a file. 
**Error?** This is an argument error, we gave it the wrong type of argument, a path to a file instead of a directory. 

# LS COMMAND
## No argument command and output  
![](ls_noarg.png)  
**Working Directory:** /home/lecture1
**Explanation:** This output lists the files and folders in the current working directory. 
**Error?** No error

## Directory as an argument command and output  
![](ls_directory.png)  
**Working Directory:** /home/lecture1
**Explanation:** When the ls command was given a directory, the output didn't actually change from having no argument, because ls listed the files in our working directory, which is the same directory as our working directory when I called ls no argument. 
**Error?** I don't think there is an error here. 

## File as an argument command and output  
![](ls_file.png)  
**Working Directory:** /home/lecture1
**Explanation:** The output is the path of the file I gave to the argument. I think since we gave it a path to a file, it will only list the file as there are no other files or directories within to list. 
**Error?** I do not believe this is an error. maybe not a good use of the command? Not entirely sure.

# CAT COMMAND
## No argument command and output  
**No output, command: [user@sahara ~/lecture1]$ cat**
**Working Directory:** /home/lecture1
**Explanation:** I believe this lack of output is because the cat command is supposed to read the content from the file in the argument and produce its contents as output, but we did not give it an argument. 
**Error?** I don't think so, I just think it needs a file in the argument, so maybe not a good use of the command that is working.  

## Directory as an argument command and output  
![](cat_directory.png)  
**Working Directory:** /home/lecture1
**Explanation:** This output is given because the cat command scans the contents of a file and produces them as output. However, we are giving the command a directory, with multiple files inside of it. 
**Error?** I believe that this is an argument error, we gave it the wrong type of argument. The cat command takes a file and outputs its contents, but we gave the cat command a directory. 

## File as an argument command and output  

**Working Directory:** 
**Explanation:** 
**Error?**
