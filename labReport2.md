# **Lab Report 2 - Servers and Bugs**

## *Part 1 - StringServer Web Page* 
The purpose of this web server is to take in a parameter throught the path and display it on the page as a list of strings. Each new input will start on a new line 

The code for my StringServer is as follows: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-29%20at%207.16.04%20PM%20(2).png)

One example of using /add-message: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-29%20at%207.15.19%20PM.png)

In this example, the main method in the StringServer class and the handleRequest method in the Handler classed are called, in which the main method takes in some array of command-line arguments from the URI, for the program to locate which port to run the server on. As for the handleRequest method, it takes in a URI, or link of the webpage, and depending on what is inputted, if the URI contains '/add', then the query gets split at the '='. The webpage is updated to reflect the most recent entry while also displaying older ones based on the query and URI. After this, the method returns what string is after the '=' and displays it on the web server. The other case of this method is where if the URI does not contain '/add' then a 404 error is returned. 

Another example: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-29%20at%207.15.35%20PM.png)

As for this example, the maing method and handleRequest method in their respective classes are called once again. The webpage is updated to reflect the most recent input while also displaying older ones based on the query and URI. This time, the string after the query is concatenated with the current string displayed with a new line as well. Since "Hi, there!" was already displayed, then the "My name is Shawn" is concatenated with that on a new line, all because the URI contained '/add'.

## *Part 2 - Identifying Bugs* 
For this part, I chose the ReverseInPlace method from lab 3 in ArrayExamples.java. What the method is meant to do is to return the elements in the array in reversed order. 

A failure-inducing input was { 1, 2, 3 }. 
The test looks like this in the Junit file: 

```
@Test
 public void testReverseInPlace() {
   int[] input1 = { 1,2,3 };
   ArrayExamples.reverseInPlace(input1);
   assertArrayEquals(new int[]{ 3,2,1 }, input1);
 }
```

As for an input that did not produce a failure-inducing input was an empty array {}. 

```
@Test
  public void testReverseInPlace() {
    int[] input1 = {};
    assertArrayEquals(new int[]{}, ArrayExamples.reversed(input1));
  }
```
The symptom of the tests looked like this: 

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-01-30%20at%203.28.21%20PM.png)

Before fixing the bug in the code. It looked like this: 

```
static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arr[arr.length - i - 1];
    }
}
```

I fixed the bug by creating a temporary array to copy the elements in reverse order then copied the elements from the temp array back into the original array: 

```
 static void reverseInPlace(int[] arr) {
   int [] temp = new int [arr.length];
   for(int i = 0; i < arr.length; i += 1) {
     temp[i] = arr[arr.length - 1 - i];
   }
   for (int i = 0; i < arr.length; i++) {
     arr[i] = temp[i];
   }
 }
```

## *Part 3 - What I Have Learned* 

Throughout the last couple labs, I have learned numerous things, including how to build my own local web server and edit it depending on paths/queries/URIs, using Junit to test code as we were barely just starting with how to use it in CSE 12, so this lab where we experimented with Junit greatly helped with what I had to do in that course as well. Although Junit is fairly tedious and annoying in some cases, it really makes a huge difference in debugging code, as you can see for yourself what outputs to expect and what it actually was, rather than manually testing code through print statements and commenting things out. 
  
 
