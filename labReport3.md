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
grep -r "Columbus" written_2/travel_guides/berlitz1 
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
