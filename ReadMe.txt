This set of scripts can be used as a prototype to collect data from public accounts on Twitter, 
extract geographic data and add a mark for each location on a map.

The main script of "tweet_reader.py" can be used to collect such data from the official account 
of the Fire Fighting Unit of Greece (@pyrosvestiki - Twitter profile).

The overall operation is described as follow:
-> Run "tweet_reader.py" file to launch the operation
1. Collection of latest tweets from @pyrosvestiki (default number = 100).
2. Text editing for each tweet to extract information containing geographic data.
   Note: This is possible through a homemade algorithm or using a NER task (default: homemade algorithm)
3. Location attributing for each geographic data per tweet.
4. Map marking for each location.
5. Data recording on HTML file called "map" that can be opened via a common Web Browser.

Version 0.0 
Developer: Georgios Patridas

Future work:
- Improvement of algorithm for geographic data recognition
- Improvement of graphics and connection with information per mark on map
- Statistical analysis of geographic data returned from this program compared to geographic data of original text
- Use of several public accounts as sources of tweets 
