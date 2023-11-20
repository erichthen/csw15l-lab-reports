## Erich Then - Lab Report 4: Doing steps 4-9 from Week 7 lab

### Step Four: logging into my ieng6 account  
!()[loggingin.png]  
#### This step consisted of me copying my ssh command from a saved google doc in an open window using Ctrl+C and Ctrl+V, and pressing enter.  
Keys Pressed: `<Ctrl>` + C , `<Ctrl>` + V , `<enter>`  

### Step Five: Cloning the fork of lab7 from Github using SSH URL  
!()[cloningssh.png]
#### For this step, I did a very similar process of the last step. I also have the ssh url clone link in a saved google doc, so I once again copied, pasted, and entered. This cloned the fork of my repositary, so I can edit it as my own. 
Keys Pressed: `<Ctrl>` + C , `<Ctrl>` + V , `<enter>`  

### Step Six: Initial run of tests, inducing a failure   
!()[failed.png]  
#### For this step, I used the shortcut of the terminal history and pressed up 4 times to pull up the *javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar * .java* command to compile the tests and pressed enter, and then up 3 times to get the *java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamples* command to run and entered. These commands set up the tests so they can be run on the ListExamples.java file.  
Keys Pressed: `<up><up><up><up><enter>` , `<up><up><up><enter>`  

### Step Seven: Fixing the file  
!()[correction1.png]  
!()[correction2.png]  
#### The first thing I did when I got to this step is used the vim ListExamples.java command to open the vim editor on this file. Then, I prompted the : command search and typed in 44, the line to correct. Once the cursor was on the first character in "index1", I pressed e in normal mode to get the cursor straight to the last character in "index1". I then pressed "r" and typed in 2. Then, I pressed colon,w,q to exit and save. Commands used: vim, :<line number>, e(go to end of word), r(replace), and :wq (saves the changes and closes editor).  
Keys Pressed: `<vim><SPACE><ListExamples.java><:44><e><r><2><:wq>'  

### Step Eight: Final run of tests, inducing success  
!()[passed.png]  
#### Similar to step six for the process, except a different number of up arrow keys to get to the commands again from the terminal history. I pressed up three times to get the compile command, enter, up two times to get back to the command to run the tests and entered. Once again, these commands compile and execute the tests on the file ListExamples.java, which has now been corrected as the output shows.  
Keys Pressed: `<up><up><up><enter>` , `<up><up><enter>`  

## Step Nine: Committing and Pushing the changes to my GitHub account  
!()[addcommitpush.png]  
#### The first command I used once I saw the failure free output from the last step I did the git add command, which added the change I made to the working directory of my repository, telling git to include this update in the following commit. I am unsure if this was necessary, but I saw it was done in lecture before the commit and push so I did it. Then, I used the commit command, which will record these changes and I included a message with it. Finally, I used the git push origin command, which pushes the changes I made to the remote repository.  
Keys Pressed: `<git><SPACE><add><SPACE><ListExamples.java><enter>` , `<git><SPACE><commit><SPACE><-m><SPACE>` , "updating ListExamples.java for labreport 4 - erich" , `<enter>` , `<git><SPACE><push><SPACE><origin><enter>`  






