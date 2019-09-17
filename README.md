# lotr
Web scraping of Lord of the Ring's characters wikis + analysis of their spoken words in films

This is a snippet from a project I did for my first Python course in grad school. The assignment was to scrape two disparate web sources,
including one wiki/wikipedia page, pertaining to a single topic and merge the data for some analytical task. As a fan of Lord of the Rings films,
I decided to scrape the LOTR fandom wiki (https://lotr.fandom.com/wiki/Main_Page) and to compare the lengths of various entries on the series'
characters with the number of words those characters spoke in the films. The spoken words were found from a Kaggle dataset 
(https://www.kaggle.com/paultimothymooney/lord-of-the-rings-data)

This code performs the relevant data manipulation (accounting for misspelled character names, accents from Tolkien's lagnugage, etc.) and 
scrapes the page lengths in characters from the Wiki. I then compare the lengths with the number of spoken words frmo the other dataset in a 
simple scatter. Some findings were that the films are highly male-dominated, with only about 8% of all spoken words said by female characters.
Interestingly, there's a high correlation among the wiki lengthhs and spoken words for those female characters. 
