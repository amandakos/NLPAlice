# NLPAlice
Using a Project Gutenberg version of Alice in Wonderland, the Python Beautiful Soup package is used to scrape words for frequency counts.
Using requests, bs4, nltk, matplotlib, and seaborn packages to webscrape words from a website.
Project Gutenberg's ebook Alice in Wonderland serves as the website from which to extract tokens.
The requests package is used to extract the data.
The BeautifulSoup function is used to parse words from the webpage.
Then RegexpTokenizer funtion is used to create tokens from words on the webpage.
From there, some wrangling is done to remove capitalization and stopwords.
Lastly, a plot is created with the frequency distribution of the 25 most common words in the ebook.
