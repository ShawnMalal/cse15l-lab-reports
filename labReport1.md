# **How to log into a course-specific account on ieng6.**


## *Part 1 - How to install Visual Studio Code (VS code)*
  If you already have VS code installed, you can skip this part and move onto Part 2!

* The first step is to go to the Visual Studio Code official website [Visual Studio Code Download](https://code.visualstudio.com/) which should look something like this:
![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-12%20at%208.43.30%20PM.png) 
  There are separate versions for both Mac OS and Windows OS along with specific instructions on downloading both so make sure to follow them carefully. 
* Once you have successfully installed VS code, open it up and the pop-up should look something like this (although the color and menu bar may differ         depending on your system's settings).
![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-11%20at%201.17.41%20PM.png)


## *Part 2 - Connecting to the Remote Server*
**Note:** Whenever you see any sort of code in a block like `this` then we are referring to the code running on the remote server 
  The goal in this part of the tutorial is to connect to a course-specific account which will be done so by using the VS Code terminal to connect to a       remote computer over the internet. 
  
  If you are on a Windows Operating System, make sure to go to this link [Git for Windows](https://gitforwindows.org/) to download Git for your system. 
  
  Once you have installed Git, follow the instructions in this post to set your default terminal to use the installed git-bash in VS Code: 
  
  [How to use Bash on Windows in VS Code](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994) 
  
  To access your UCSD course-specific account, go to this website and login with your credentials
  
  [Access your course-specific account here](https://sdacs.ucsd.edu/~icc/index.php)
  
  If you need any help with resetting your password, go to this tutorial and follow the instructions carefully: 
  
  [Tutorial on how to reset your course-specific account's password](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit)
  
Now that everything is set up, open up your own VS Code terminal (Ctrl or Command + backtick , or use the Terminal → New Terminal menu option). Then, to use ssh, the command you must input in the terminal will look exactly like this, except you replace the 'zz' with your course-specific account.  

> $ ssh cs15lwi23zz@ieng6.ucsd.edu

The '$' symbol is there for reference to the terminal, no need to type it. 

If this is the first time you are connecting to the remote server (which it most likely is), then it should look like this: 

> ⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
> The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
> RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
> Are you sure you want to continue connecting (yes/no/[fingerprint])?

Assuming this is what it looks like, type and enter 'yes' in the terminal. The terminal will then prompt you to give your password, which is the password to your 'ieng6' account.

> ⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
> The authenticity of host 'ieng6-202.ucsd.edu (128.54.70.227)' can't be established.
> RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
> Are you sure you want to continue connecting (yes/no/[fingerprint])? 
> Password: 

Enter your password and your client should now have connected to the remote server and the terminal should now look like this: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-11%20at%202.21.47%20PM.png)

Now you are finally connected to the remote server! Your terminal is now connected to a computer in the CSE basement, so any commands you run now, will run on that computer as well. 

## *Part 3 - Trying some commands* 

Now that you are connected to the remote server, try commands like -> 'cd', 'ls', 'pwd', 'mkdir', 'cp'.
For some additional specific commands, try:

* cd ~
* cd
* ls -lat
* ls -a
* ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23abc, where the abc is another user's username
* cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/
* cat /home/linux/ieng6/cs15lwi23/public/hello.txt
  
When running a command like ls -lat, your terminal should display something like this: 
 
![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-14%20at%201.05.40%20PM.png)
where it lists some extension files
  
Trying another command, such as 'cat /home/linux/ieng6/cs15lwi23/public/hello.tx' will prompt you with a hello message
  
> Hello! Welcome to CSE 15L
  
Well, that's it for the tutorial! You now know how to access the remote server in the CSE basement and can run some commands both on your client server (own terminal) and the remote server (terminal that is shared with a computer in the CSE basement). 








  
  
