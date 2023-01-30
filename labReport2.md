# **Lab Report 2 - Servers and Bugs**

## *Part 1 - StringServer Web Page* 
The purpose of this web server is to take in a parameter throught the path and display it on the page as a list of strings. Each new input will start on a new line 

The code for my StringServer is as follows: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-29%20at%207.16.04%20PM%20(2).png)

One example of using /add-message: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-29%20at%207.15.19%20PM.png)

In this example, the main method in the StringServer class and the handleRequest method in the Handler classed are called, in which the main method takes in some array of command-line arguments from the URI, for the program to locate which port to run the server on. As for the handleRequest method, it takes in a URI, or link of the webpage, and depending on what is inputted, if the URI contains '/add', then the query gets split at the '='. The webpage is updated to reflect the most recent entry while also displaying older ones based on the query and URL. After this, the method returns what string is after the '=' and displays it on the web server. The other case of this method is where if the URI does not contain '/add' then a 404 error is returned. 

Another example: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-29%20at%207.15.35%20PM.png)

As for this example, the maing method and handleRequest method in their respective classes are called once again. The webpage is updated to reflect the most recent entry while also displaying older ones based on the query and URL. This time, the string after the query is concatenated with the current string displayed with a new line as well. Since "Hi, there!" was already displayed, then the "My name is Shawn" is concatenated with that on a new line, all because the URI contained '/add'.

## *Part 2 - Identifying Bugs* 




