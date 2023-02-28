# **Lab Report 4 - Using Terminal Shortcuts**

## *Step 1* 

The first thing I did was to manually type out the ssh login dedicated to my account to connect to the remote server, in which it looks like this: 

```
ssh cs15lwi23acd@ieng6.ucsd.edu
```
Then pressed `<enter>` to succssfully login 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%206.41.22%20PM.png)

## *Step 2*
Since the last time I have done this lab, the commands have been saved in the command history through the remote server, so to clone the repository,

The Keys pressed: `<up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <enter>` which amounts to 14 times in order to get to the command, which is: 

```
git clone git@github.com:ShawnMalal/lab7.git
```
Once entered, the terminal output should look like this: 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%206.47.40%20PM.png)

## *Step 3*
The next step is to demonstrate that there is a bug in the ListExamples file. 

Keys pressed: `cd lab7 <enter>` `<up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <enter>` `<up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <enter>` 

These keys ran the commands: 

```
cd lab7
```

```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
```
and 
```
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```

Which gave the output, demonstrating that the tests fail: 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%207.53.41%20PM.png)

