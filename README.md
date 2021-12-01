# ATOM Web search engine 

ATOM is developed in java on Eclipse IDE.

Features implemented -
Web crawling using spiderbot
HTML to text using jsoup
Pattern searching using Boyre Moore
Page Ranking using page ranking algorithm

Flow of execution -
1. At the start of the program, the user needs to input the URL to be crawled.
2. Web crawling occurs 
3. HTML to text conversion occurs using Jsoup library
4. The user inputs the word to be searched
5. If the word is not found then the program asks the user whether they want to continue or not
6. If the user says no, the program ends
7. If the word is found then pattern searching occurs using Boyre Moore algorithm
8. The pages are ranked using the Page ranking algorithm (which uses sorting)
