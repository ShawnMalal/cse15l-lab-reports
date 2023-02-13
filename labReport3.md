# **Lab Report 3 - Researching Commands: grep**


## *grep -r*
Using the -r command causes the terminal to recursively search through all directories for text files that contain the specified pattern/string.
- Source(s) used: grep --help

``` 
$ grep -r "Lucayans" written_2/
written_2/travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and 
the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
```


```
$ grep -r "Columbus" written_2/travel_guides/berlitz1 
written_2/travel_guides/berlitz1/HistoryJamaica.txt:        Columbus and the Arrival of Europeans
written_2/travel_guides/berlitz1/HistoryJamaica.txt:        Columbus first arrived in Jamaica on 5 May 1494 at Discovery
written_2/travel_guides/berlitz1/HistoryJamaica.txt:        from Cuba. After the death of Columbus in 1505, Jamaica became the
written_2/travel_guides/berlitz1/IntroMadeira.txt:        b.c. , Madeira was discovered only a few decades before Columbus made
written_2/travel_guides/berlitz1/IntroMadeira.txt:        of Porto Santo. Christopher Columbus visited Porto Santo in the second
written_2/travel_guides/berlitz1/IntroMadeira.txt:        the wake of Columbus and dock on the neighboring island of Porto Santo,
written_2/travel_guides/berlitz1/HistoryMallorca.txt:        Christopher Columbus, the seafaring captain from Genoa (whom at least
written_2/travel_guides/berlitz1/HistoryMallorca.txt:        Columbus crossed the Atlantic, landing in the Caribbean islands.
written_2/travel_guides/berlitz1/WhereToItaly.txt:        annals forever as the birthplace of Christopher Columbus. The
written_2/travel_guides/berlitz1/WhereToItaly.txt:        Columbus. The closest reference you’ll find is on a ramp leading to the
written_2/travel_guides/berlitz1/WhereToJapan.txt:        Kamakura-style hall, is believed to be what Columbus was after in his
written_2/travel_guides/berlitz1/HistoryMadeira.txt:        the island’s future wine trade. Christopher Columbus, not yet a sailor
written_2/travel_guides/berlitz1/HistoryMadeira.txt:        shipment. Yet Columbus (Columbo in Portuguese) returned six years
written_2/travel_guides/berlitz1/HistoryMadeira.txt:        Columbus had his eye on more than sugar in Madeira. He
written_2/travel_guides/berlitz1/HistoryMadeira.txt:        that it was due to his time spent there that Christopher Columbus
written_2/travel_guides/berlitz1/WhereToMallorca.txt:        birthplace of Columbus. Sóller and Palma are linked by the narrow-gauge
written_2/travel_guides/berlitz1/IntroFWI.txt:        haven’t changed much since Columbus claimed these remote outposts for
written_2/travel_guides/berlitz1/IntroJamaica.txt:        they have slightly changed the story of Columbus and his trip to the
written_2/travel_guides/berlitz1/IntroJamaica.txt:        other islands. As someone has said, Columbus only thought that he had
written_2/travel_guides/berlitz1/IntroJamaica.txt:        discovered him — Columbus was really lost, thinking that he had found
written_2/travel_guides/berlitz1/WhereToMadeira.txt:        Columbus (who may have lived in Funchal for a while), and, close by,
written_2/travel_guides/berlitz1/WhereToMadeira.txt:        its link to Christopher Columbus. The town’s major attraction is a
written_2/travel_guides/berlitz1/WhereToMadeira.txt:        The story of Columbus and the Madeiran archipelago is not
written_2/travel_guides/berlitz1/WhereToMadeira.txt:        Columbus married Felipa Moniz Perestrelo, the daughter of the first
written_2/travel_guides/berlitz1/WhereToMadeira.txt:        around 1480 Columbus lived here for about two years and that young
written_2/travel_guides/berlitz1/WhereToMadeira.txt:        the man himself. Another curious enigma about Columbus that has baffled
written_2/travel_guides/berlitz1/HistoryIbiza.txt:        in 1492 Christopher Columbus sailed westwards and discovered America.
written_2/travel_guides/berlitz1/HistoryFWI.txt:        islands of the Far East, Christopher Columbus first discovered Dominica
written_2/travel_guides/berlitz1/HistoryFWI.txt:        crown, Columbus named one Saint-Barthélemy after his brother and
written_2/travel_guides/berlitz1/HistoryFWI.txt:        Columbus reach Martinique.
written_2/travel_guides/berlitz1/WhereToMadrid.txt:        Christopher Columbus and a monument to the discovery of the New World.
written_2/travel_guides/berlitz1/WhatToJamaica.txt:        the place where Columbus landed in 1494 on his second journey from
written_2/travel_guides/berlitz1/WhatToJamaica.txt:        Columbus Park is built on land donated by the Kaiser Bauxite Company,
written_2/travel_guides/berlitz1/WhatToJamaica.txt:        west of the modern town. Columbus is said to have landed here in 1503
written_2/travel_guides/berlitz1/WhatToJamaica.txt:        archaeologists to locate them, they have never been found. Columbus
written_2/travel_guides/berlitz1/WhereToFWI.txt:        Columbus named it after his favorite Spanish monastery, Our
written_2/travel_guides/berlitz1/WhereToFWI.txt:        Christopher Columbus perched atop a column in a little roadside square.
written_2/travel_guides/berlitz1/WhereToFWI.txt:        Columbus.
written_2/travel_guides/berlitz1/WhereToFWI.txt:        its extensive sugarcane fields, was named by Columbus after the ship
written_2/travel_guides/berlitz1/WhereToFWI.txt:        first of the Antilles spotted by Columbus in 1493. If you like early
written_2/travel_guides/berlitz1/WhereToFWI.txt:        the most colorful tropical gardens on earth. When Columbus discovered
written_2/travel_guides/berlitz1/WhereToFWI.txt:        Columbus named the island after St. Martin on that saint’s
written_2/travel_guides/berlitz1/WhereToFWI.txt:        Known fondly as “St. Barts,” Columbus bestowed his brother’s name,
```
The results may be long, but grep -r indeed was able to find all files that have the string "Columbus" and all the files with the string "Lucayans". This is useful when trying to find a file with a specific word in mind or could be used to find data.  

## *grep --color*
Using the --color command causes the terminal to highlight the matching patterns as the output
- Source(s) used: Chatgpt
- For this specific command, I had to use screenshots to show the highlighted colors!

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-12%20at%208.00.06%20PM.png)

![image](https://raw.githubusercontent.com/ShawnMalal/cse15l-lab-reports/main/Screenshot%202023-02-12%20at%208.03.17%20PM.png)

This command could be VERY useful, such as if you are trying to find some matching data in a txt file, this command would be able to highlight that. 

## *grep -n* 
Using the -n command causes the terminal to return the specific lines that contain the specified pattern in the command, with the line numbers corresponding to it.
- Source(s) used: ChatGPT!

```
$ grep -n "Lucayans" ./written_2/travel_guides/berlitz2/Bahamas-History.txt
6:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
7:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
```


```
$ grep -n "America" written_2/travel_guides/berlitz1/HistoryFWI.txt  
15:        America began migrating up the Antilles chain, reaching Martinique and
25:        These Indians, also from South America, swept north in fast
50:        Lesser Antilles. The big prize was gold, particularly in South America,
122:        During the American War of Independence, France’s
123:        sympathies were undisguised: American ships were granted safe anchorage
150:        leading to a diplomatic blow-up with the new American government.
```
This command can also be useful with any data related files, such as finding which line the data shows up in, or if you are just curious which like a specific word shows up in. 

## *grep -c* 
Using the -c command causes the terminal to return the number of times a certain specified pattern or string appears in a text file.
- Source(s) used: Chatgpt and grep --help

```
$ grep -c "Lucayans" written_2/travel_guides/berlitz2/*.txt
written_2/travel_guides/berlitz2/Algarve-History.txt:0
written_2/travel_guides/berlitz2/Algarve-Intro.txt:0
written_2/travel_guides/berlitz2/Algarve-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Algarve-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Amsterdam-History.txt:0
written_2/travel_guides/berlitz2/Amsterdam-Intro.txt:0
written_2/travel_guides/berlitz2/Amsterdam-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Amsterdam-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Athens-History.txt:0
written_2/travel_guides/berlitz2/Athens-Intro.txt:0
written_2/travel_guides/berlitz2/Athens-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Athens-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bahamas-History.txt:2
written_2/travel_guides/berlitz2/Bahamas-Intro.txt:0
written_2/travel_guides/berlitz2/Bahamas-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bahamas-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bali-History.txt:0
written_2/travel_guides/berlitz2/Bali-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bali-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Barcelona-History.txt:0
written_2/travel_guides/berlitz2/Barcelona-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Barcelona-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Beijing-History.txt:0
written_2/travel_guides/berlitz2/Beijing-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Beijing-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Berlin-History.txt:0
written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Bermuda-history.txt:0
written_2/travel_guides/berlitz2/Bermuda-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Bermuda-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Boston-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Budapest-History.txt:0
written_2/travel_guides/berlitz2/Budapest-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Budapest-WhereoGo.txt:0
written_2/travel_guides/berlitz2/California-History.txt:0
written_2/travel_guides/berlitz2/California-WhatToDo.txt:0
written_2/travel_guides/berlitz2/California-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Canada-History.txt:0
written_2/travel_guides/berlitz2/Canada-WhereToGo.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-History.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-WhatToDo.txt:0
written_2/travel_guides/berlitz2/CanaryIslands-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Cancun-History.txt:0
written_2/travel_guides/berlitz2/Cancun-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Cancun-WhereToGo.txt:0
written_2/travel_guides/berlitz2/China-History.txt:0
written_2/travel_guides/berlitz2/China-WhatToDo.txt:0
written_2/travel_guides/berlitz2/China-WhereToGo.txt:0
written_2/travel_guides/berlitz2/CostaBlanca-History.txt:0
written_2/travel_guides/berlitz2/CostaBlanca-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Costa-History.txt:0
written_2/travel_guides/berlitz2/Costa-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Costa-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Crete-History.txt:0
written_2/travel_guides/berlitz2/Crete-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Crete-WhereToGo.txt:0
written_2/travel_guides/berlitz2/CstaBlanca-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Cuba-History.txt:0
written_2/travel_guides/berlitz2/Cuba-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Cuba-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Nepal-History.txt:0
written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Nepal-WhereToGo.txt:0
written_2/travel_guides/berlitz2/NewOrleans-History.txt:0
written_2/travel_guides/berlitz2/Paris-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Paris-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Poland-History.txt:0
written_2/travel_guides/berlitz2/Poland-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Portugal-History.txt:0
written_2/travel_guides/berlitz2/Portugal-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Portugal-WhereToGo.txt:0
written_2/travel_guides/berlitz2/PuertoRico-History.txt:0
written_2/travel_guides/berlitz2/PuertoRico-WhatToDo.txt:0
written_2/travel_guides/berlitz2/PuertoRico-WhereToGo.txt:0
written_2/travel_guides/berlitz2/Vallarta-History.txt:0
written_2/travel_guides/berlitz2/Vallarta-WhatToDo.txt:0
written_2/travel_guides/berlitz2/Vallarta-WhereToGo.txt:0
```


```
$ grep -c "America" written_2/travel_guides/berlitz1/*.txt           
written_2/travel_guides/berlitz1/HandRHawaii.txt:0
written_2/travel_guides/berlitz1/HandRHongKong.txt:0
written_2/travel_guides/berlitz1/HandRIbiza.txt:0
written_2/travel_guides/berlitz1/HandRIsrael.txt:6
written_2/travel_guides/berlitz1/HandRIstanbul.txt:0
written_2/travel_guides/berlitz1/HandRJamaica.txt:3
written_2/travel_guides/berlitz1/HandRJerusalem.txt:0
written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HandRLasVegas.txt:2
written_2/travel_guides/berlitz1/HandRLisbon.txt:0
written_2/travel_guides/berlitz1/HandRLosAngeles.txt:0
written_2/travel_guides/berlitz1/HandRMadeira.txt:0
written_2/travel_guides/berlitz1/HandRMadrid.txt:0
written_2/travel_guides/berlitz1/HandRMallorca.txt:0
written_2/travel_guides/berlitz1/HistoryDublin.txt:2
written_2/travel_guides/berlitz1/HistoryEdinburgh.txt:0
written_2/travel_guides/berlitz1/HistoryEgypt.txt:0
written_2/travel_guides/berlitz1/HistoryFWI.txt:6
written_2/travel_guides/berlitz1/HistoryFrance.txt:3
written_2/travel_guides/berlitz1/HistoryGreek.txt:0
written_2/travel_guides/berlitz1/HistoryHawaii.txt:13
written_2/travel_guides/berlitz1/HistoryHongKong.txt:2
written_2/travel_guides/berlitz1/HistoryIbiza.txt:2
written_2/travel_guides/berlitz1/HistoryIndia.txt:1
written_2/travel_guides/berlitz1/HistoryIsrael.txt:2
written_2/travel_guides/berlitz1/HistoryIstanbul.txt:1
written_2/travel_guides/berlitz1/HistoryItaly.txt:2
written_2/travel_guides/berlitz1/HistoryJamaica.txt:5
written_2/travel_guides/berlitz1/HistoryJapan.txt:5
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:0
written_2/travel_guides/berlitz1/HistoryLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HistoryLasVegas.txt:5
written_2/travel_guides/berlitz1/HistoryMadeira.txt:2
written_2/travel_guides/berlitz1/HistoryMadrid.txt:1
written_2/travel_guides/berlitz1/HistoryMalaysia.txt:2
written_2/travel_guides/berlitz1/HistoryMallorca.txt:2
written_2/travel_guides/berlitz1/IntroDublin.txt:0
written_2/travel_guides/berlitz1/IntroEdinburgh.txt:0
written_2/travel_guides/berlitz1/IntroEgypt.txt:0
written_2/travel_guides/berlitz1/IntroFWI.txt:1
written_2/travel_guides/berlitz1/IntroFrance.txt:0
written_2/travel_guides/berlitz1/IntroGreek.txt:0
written_2/travel_guides/berlitz1/IntroHongKong.txt:1
written_2/travel_guides/berlitz1/IntroIbiza.txt:0
written_2/travel_guides/berlitz1/IntroIndia.txt:1
written_2/travel_guides/berlitz1/IntroIsrael.txt:0
written_2/travel_guides/berlitz1/IntroIstanbul.txt:0
written_2/travel_guides/berlitz1/IntroItaly.txt:0
written_2/travel_guides/berlitz1/IntroJamaica.txt:1
written_2/travel_guides/berlitz1/IntroJapan.txt:3
written_2/travel_guides/berlitz1/IntroJerusalem.txt:2
written_2/travel_guides/berlitz1/IntroLakeDistrict.txt:0
written_2/travel_guides/berlitz1/IntroLasVegas.txt:7
written_2/travel_guides/berlitz1/IntroLosAngeles.txt:3
written_2/travel_guides/berlitz1/IntroMadeira.txt:2
written_2/travel_guides/berlitz1/IntroMadrid.txt:0
written_2/travel_guides/berlitz1/IntroMalaysia.txt:0
written_2/travel_guides/berlitz1/IntroMallorca.txt:0
written_2/travel_guides/berlitz1/JungleMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToDublin.txt:0
written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:0
written_2/travel_guides/berlitz1/WhatToEgypt.txt:0
written_2/travel_guides/berlitz1/WhatToFWI.txt:9
written_2/travel_guides/berlitz1/WhatToFrance.txt:1
written_2/travel_guides/berlitz1/WhatToGreek.txt:0
written_2/travel_guides/berlitz1/WhatToHawaii.txt:0
written_2/travel_guides/berlitz1/WhatToHongKong.txt:1
written_2/travel_guides/berlitz1/WhatToIbiza.txt:2
written_2/travel_guides/berlitz1/WhatToIndia.txt:2
written_2/travel_guides/berlitz1/WhatToIsrael.txt:0
written_2/travel_guides/berlitz1/WhatToIstanbul.txt:0
written_2/travel_guides/berlitz1/WhatToItaly.txt:0
written_2/travel_guides/berlitz1/WhatToJamaica.txt:3
written_2/travel_guides/berlitz1/WhatToJapan.txt:3
written_2/travel_guides/berlitz1/WhatToLakeDistrict.txt:1
written_2/travel_guides/berlitz1/WhatToLasVegas.txt:2
written_2/travel_guides/berlitz1/WhatToLosAngeles.txt:2
written_2/travel_guides/berlitz1/WhatToMadeira.txt:1
written_2/travel_guides/berlitz1/WhatToMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToMallorca.txt:0
written_2/travel_guides/berlitz1/WhereToDublin.txt:3
written_2/travel_guides/berlitz1/WhereToEdinburgh.txt:1
written_2/travel_guides/berlitz1/WhereToEgypt.txt:0
written_2/travel_guides/berlitz1/WhereToFWI.txt:5
written_2/travel_guides/berlitz1/WhereToFrance.txt:8
written_2/travel_guides/berlitz1/WhereToGreek.txt:0
written_2/travel_guides/berlitz1/WhereToHawaii.txt:0
written_2/travel_guides/berlitz1/WhereToHongKong.txt:2
written_2/travel_guides/berlitz1/WhereToIbiza.txt:1
written_2/travel_guides/berlitz1/WhereToIndia.txt:0
written_2/travel_guides/berlitz1/WhereToIsrael.txt:4
written_2/travel_guides/berlitz1/WhereToIstanbul.txt:1
written_2/travel_guides/berlitz1/WhereToItaly.txt:8
written_2/travel_guides/berlitz1/WhereToJapan.txt:10
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:3
written_2/travel_guides/berlitz1/WhereToLakeDistrict.txt:0
written_2/travel_guides/berlitz1/WhereToLosAngeles.txt:14
written_2/travel_guides/berlitz1/WhereToMadeira.txt:1
written_2/travel_guides/berlitz1/WhereToMadrid.txt:2
written_2/travel_guides/berlitz1/WhereToMalaysia.txt:4
written_2/travel_guides/berlitz1/WhereToMallorca.txt:0
```
Once again, this type of command could be VERY useful with any data related files, as you are able to easily access how many times a specific pattern shows up within any single file or many files. 


Overall, the grep command seems very useful for searching for specific patterns which could be very useful when it comes to some sort of data reading. 





