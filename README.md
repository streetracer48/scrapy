# scrapy

* For  scraping I'm  going to use the very popular Python library called BeautifulSoup.
  BeautifulSoup installed on my system with python version 3+. (pip install beautifulsoup4)

* Since my aim is to extract the entire body of the apartments-for-sale page,After you inspect a webpage then  identify the <div> tag. 
  then I found   <div class="Grid-Cell w(100%)"> </div> is the tag I actually  looking for. then  straight dive into the code and do scraping!

* step three I begin parsing the webpage and searching for the specific elements. I need  to use BeautifulSoup For connecting to the website and getting the HTML I using Python’s urllib. then imported required libraries.

* We now iterate through content to find  the City-List tags in it to get the entire body of the tag.


