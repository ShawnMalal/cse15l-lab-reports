# **Lab Report 4 - Using Terminal Shortcuts**

## *Step 1 - ssh into remote server* 

The first thing I did was to manually type out the ssh login dedicated to my account to connect to the remote server, in which it looks like this: 

```
ssh cs15lwi23acd@ieng6.ucsd.edu
```
Then pressed `<enter>` to succssfully login 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%206.41.22%20PM.png)

## *Step 2 - Clone the Repository*
Since the last time I have done this lab, the commands have been saved in the command history through the remote server, so to clone the repository,

The Keys pressed: `<up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <enter>` which amounts to 14 times in order to get to the command, which is: 

```
git clone git@github.com:ShawnMalal/lab7.git
```
Once entered, the terminal output should look like this: 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%206.47.40%20PM.png)

## *Step 3 - Demonstrate failed tests*
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
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples
```

Which gave the output, demonstrating that the tests fail: 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%208.37.33%20PM.png)

## *Step 4 - Edit the file/Fix the code through nano*
Now, to fix the error within the ListExamples.java file, I typed in ``` nano ListExamples.java``` and got to a screen that looks like this: 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%208.13.03%20PM.png)

To fix the error, I pressed the key `<down>` 42 times, and then `<right>` 12 times, then `<backspace>` 1 time, then typed in 2, to edit the line from ```index1 += 1;``` to ```index2 += 1;```

Then, I pressed the keys: `<Cntrl + O>`, `<enter>` and `<Cntrl + x>` to save and exit the file that was edited by me. 

## *Step 5 - Demonstrating that the test cases now pass*

Keys pressed: ```<up> <up> <up> <enter>``` and ```<up> <up> <up> <enter>```

Which then ran the same java commands for running the tests: 

```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
```
and 
```
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples
```
The output in the terminal now demonstrate that the test cases pass: 

![Image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-27%20at%208.42.06%20PM.png)
