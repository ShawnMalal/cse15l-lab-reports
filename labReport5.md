# **Lab Report 5 - Researching More Commands: find**

In my last lab report regarding commands, I explored *grep*, and now I will look into the command *find* and demonstrate various options through it.

## *find -name*
Using the -name option searches for files or directories with a specific name. 
- Source(s) used: ChatGPT, find manual
```
shawnmalal@Shawns-MBP skill-demo1-data % find written_2 -name  "*WhatToDo.txt"
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt
written_2/travel_guides/berlitz2/Poland-WhatToDo.txt
written_2/travel_guides/berlitz2/Cuba-WhatToDo.txt
written_2/travel_guides/berlitz2/Cancun-WhatToDo.txt
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt
written_2/travel_guides/berlitz2/Bermuda-WhatToDo.txt
written_2/travel_guides/berlitz2/Budapest-WhatToDo.txt
written_2/travel_guides/berlitz2/PuertoRico-WhatToDo.txt
written_2/travel_guides/berlitz2/Vallarta-WhatToDo.txt
written_2/travel_guides/berlitz2/Bali-WhatToDo.txt
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt
written_2/travel_guides/berlitz2/Bahamas-WhatToDo.txt
written_2/travel_guides/berlitz2/Barcelona-WhatToDo.txt
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt
written_2/travel_guides/berlitz2/Costa-WhatToDo.txt
written_2/travel_guides/berlitz2/Crete-WhatToDo.txt
written_2/travel_guides/berlitz2/CanaryIslands-WhatToDo.txt
written_2/travel_guides/berlitz2/California-WhatToDo.txt
written_2/travel_guides/berlitz2/China-WhatToDo.txt
written_2/travel_guides/berlitz2/Athens-WhatToDo.txt
written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt
written_2/travel_guides/berlitz2/Paris-WhatToDo.txt
written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt
```
```
shawnmalal@Shawns-MBP skill-demo1-data % find written_2 -name  "*WhereToGo.txt"
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt
written_2/travel_guides/berlitz2/Amsterdam-WhereToGo.txt
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt
written_2/travel_guides/berlitz2/Portugal-WhereToGo.txt
written_2/travel_guides/berlitz2/Boston-WhereToGo.txt
written_2/travel_guides/berlitz2/California-WhereToGo.txt
written_2/travel_guides/berlitz2/Bahamas-WhereToGo.txt
written_2/travel_guides/berlitz2/Crete-WhereToGo.txt
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt
written_2/travel_guides/berlitz2/Bali-WhereToGo.txt
written_2/travel_guides/berlitz2/Barcelona-WhereToGo.txt
written_2/travel_guides/berlitz2/Athens-WhereToGo.txt
written_2/travel_guides/berlitz2/Paris-WhereToGo.txt
written_2/travel_guides/berlitz2/China-WhereToGo.txt
written_2/travel_guides/berlitz2/CstaBlanca-WhereToGo.txt
written_2/travel_guides/berlitz2/PuertoRico-WhereToGo.txt
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt
written_2/travel_guides/berlitz2/CanaryIslands-WhereToGo.txt
written_2/travel_guides/berlitz2/Algarve-WhereToGo.txt
written_2/travel_guides/berlitz2/Beijing-WhereToGo.txt
written_2/travel_guides/berlitz2/Bermuda-WhereToGo.txt
written_2/travel_guides/berlitz2/Vallarta-WhereToGo.txt
written_2/travel_guides/berlitz2/Cancun-WhereToGo.txt
```
As seen, using -name in the written_2 directory was able to find every file that are titled "WhatToDo.txt and WhereToGo.txt". 

## *find -s*
Using the -s option causes the terminal to find all files with the given argument, while also outputting the files in a sorted list. 
- Source(s) used: ChatGPT, find manual

```
shawnmalal@Shawns-MBP skill-demo1-data % find -s written_2/non-fiction/OUP/Castro           
written_2/non-fiction/OUP/Castro
written_2/non-fiction/OUP/Castro/chA.txt
written_2/non-fiction/OUP/Castro/chB.txt
written_2/non-fiction/OUP/Castro/chC.txt
written_2/non-fiction/OUP/Castro/chL.txt
written_2/non-fiction/OUP/Castro/chM.txt
written_2/non-fiction/OUP/Castro/chN.txt
written_2/non-fiction/OUP/Castro/chO.txt
written_2/non-fiction/OUP/Castro/chP.txt
written_2/non-fiction/OUP/Castro/chQ.txt
written_2/non-fiction/OUP/Castro/chR.txt
written_2/non-fiction/OUP/Castro/chV.txt
written_2/non-fiction/OUP/Castro/chW.txt
written_2/non-fiction/OUP/Castro/chY.txt
written_2/non-fiction/OUP/Castro/chZ.txt
```
Along with that, it is also possible to sort files by the actual file name by combining the two commands

```
shawnmalal@Shawns-MBP skill-demo1-data % find -s written_2 -name "*o.txt" 
written_2/travel_guides/berlitz2/Algarve-Intro.txt
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt
written_2/travel_guides/berlitz2/Algarve-WhereToGo.txt
written_2/travel_guides/berlitz2/Amsterdam-Intro.txt
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt
written_2/travel_guides/berlitz2/Amsterdam-WhereToGo.txt
written_2/travel_guides/berlitz2/Athens-Intro.txt
written_2/travel_guides/berlitz2/Athens-WhatToDo.txt
written_2/travel_guides/berlitz2/Athens-WhereToGo.txt
written_2/travel_guides/berlitz2/Bahamas-Intro.txt
written_2/travel_guides/berlitz2/Bahamas-WhatToDo.txt
written_2/travel_guides/berlitz2/Bahamas-WhereToGo.txt
written_2/travel_guides/berlitz2/Bali-WhatToDo.txt
written_2/travel_guides/berlitz2/Bali-WhereToGo.txt
written_2/travel_guides/berlitz2/Barcelona-WhatToDo.txt
written_2/travel_guides/berlitz2/Barcelona-WhereToGo.txt
written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt
written_2/travel_guides/berlitz2/Beijing-WhereToGo.txt
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt
written_2/travel_guides/berlitz2/Bermuda-WhatToDo.txt
written_2/travel_guides/berlitz2/Bermuda-WhereToGo.txt
written_2/travel_guides/berlitz2/Boston-WhereToGo.txt
written_2/travel_guides/berlitz2/Budapest-WhatToDo.txt
written_2/travel_guides/berlitz2/Budapest-WhereoGo.txt
written_2/travel_guides/berlitz2/California-WhatToDo.txt
written_2/travel_guides/berlitz2/California-WhereToGo.txt
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt
written_2/travel_guides/berlitz2/CanaryIslands-WhatToDo.txt
written_2/travel_guides/berlitz2/CanaryIslands-WhereToGo.txt
written_2/travel_guides/berlitz2/Cancun-WhatToDo.txt
written_2/travel_guides/berlitz2/Cancun-WhereToGo.txt
written_2/travel_guides/berlitz2/China-WhatToDo.txt
written_2/travel_guides/berlitz2/China-WhereToGo.txt
written_2/travel_guides/berlitz2/Costa-WhatToDo.txt
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt
written_2/travel_guides/berlitz2/Crete-WhatToDo.txt
written_2/travel_guides/berlitz2/Crete-WhereToGo.txt
written_2/travel_guides/berlitz2/CstaBlanca-WhereToGo.txt
written_2/travel_guides/berlitz2/Cuba-WhatToDo.txt
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt
written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt
written_2/travel_guides/berlitz2/Paris-WhatToDo.txt
written_2/travel_guides/berlitz2/Paris-WhereToGo.txt
written_2/travel_guides/berlitz2/Poland-WhatToDo.txt
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt
written_2/travel_guides/berlitz2/Portugal-WhereToGo.txt
written_2/travel_guides/berlitz2/PuertoRico-WhatToDo.txt
written_2/travel_guides/berlitz2/PuertoRico-WhereToGo.txt
written_2/travel_guides/berlitz2/Vallarta-WhatToDo.txt
written_2/travel_guides/berlitz2/Vallarta-WhereToGo.txt
```

As shown, the files that end with "o.txt" were sorted by alphabetical order of their file name. 

## *find -delete*
Using the -delete option will delete the file with a specified name, and can even delete a directory by a specified name. 
- Source(s) used: ChatGPT

For this first example, I am going to demonstrate the -delete command by using it on the previous found files under  the name "WhereToGo.txt"

```
shawnmalal@Shawns-MBP skill-demo1-data % find written_2 -name  "*WhereToGo.txt" -delete
shawnmalal@Shawns-MBP skill-demo1-data % find written_2 -name  "*WhereToGo.txt"  
```
As seen, after using the -delete option, no files under the name "WhereToGo.txt" are found, meaning the deletion was successful.
For this next example, I am going to use the -delete option on a directory rather than files. 

```
shawnmalal@Shawns-MBP skill-demo1-data % cd written_2
shawnmalal@Shawns-MBP written_2 % ls
non-fiction     travel_guides

shawnmalal@Shawns-MBP written_2 % find travel_guides -delete
shawnmalal@Shawns-MBP written_2 % ls
non-fiction
```

In this example, we can see that the travel_guides directory lied in the written_2 directory, but after using -delete on it and using ls again, the travel_guides directory is no where to be found, meaning it was successfully deleted. 

## *find -print*
Using the -print option will simply print out the name of all the found files. Similar to the -name option, but print is used to print the names of files and directories that match the search criteria file path rather than a specific file name. 
Source(s) used: ChatGPT

```
shawnmalal@Shawns-MBP written_2 % find non-fiction/OUP/Berk -print
non-fiction/OUP/Berk
non-fiction/OUP/Berk/ch2.txt
non-fiction/OUP/Berk/ch1.txt
non-fiction/OUP/Berk/CH4.txt
non-fiction/OUP/Berk/ch7.txt
```
```
shawnmalal@Shawns-MBP written_2 % find non-fiction/OUP/Castro -print
non-fiction/OUP/Castro
non-fiction/OUP/Castro/chR.txt
non-fiction/OUP/Castro/chP.txt
non-fiction/OUP/Castro/chQ.txt
non-fiction/OUP/Castro/chB.txt
non-fiction/OUP/Castro/chC.txt
non-fiction/OUP/Castro/chA.txt
non-fiction/OUP/Castro/chV.txt
non-fiction/OUP/Castro/chW.txt
non-fiction/OUP/Castro/chM.txt
non-fiction/OUP/Castro/chZ.txt
non-fiction/OUP/Castro/chL.txt
non-fiction/OUP/Castro/chN.txt
non-fiction/OUP/Castro/chY.txt
non-fiction/OUP/Castro/chO.txt
```
As seen in these two examples, the files under the Berk and Castro directories were printed out. 

Overall, I enjoyed researching the find command, although researching the grep command was more interesting to me. Nonetheless, I learned a great deal from resarching these commands and will for sure use them in my every day life when working with the command-line/Terminal 


