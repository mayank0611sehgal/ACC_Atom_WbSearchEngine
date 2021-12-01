ATOM Web search engine 

ATOM is developed in java on Eclipse IDE.

Features implemented -
Web crawling using spiderbot
HTML to text using jsoup
Pattern searching using Boyre Moore
Page Ranking using page ranking algorithm

Flow of execution -
At the start of the program, the user needs to input the URL to be crawled.
Web crawling occurs 
HTML to text conversion occurs using Jsoup library
The user inputs the word to be searched
If the word is not found then the program asks the user whether they want to continue or not
If the user says no, the program ends
If the word is found then pattern searching occurs using Boyre Moore algorithm
The pages are ranked using the Page ranking algorithm (which uses sorting)
