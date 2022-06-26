# Web Scrapping Packages

## 1)Scrapy :
Scrapy is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

### Features:
- Scrapy is an open source and free to use web crawling framework.
- Scrapy generates feed exports in formats such as JSON, CSV, and XML.
- Scrapy has built-in support for selecting and extracting data from sources either by XPath or CSS expressions.
- Scrapy based on crawler, allows extracting data from the web pages automatically.

### Limitations:

- Scrapy is only for Python 2.7 or more than that.
- Installation is different for different operating systems.

### References:

https://docs.scrapy.org/en/latest
https://www.tutorialspoint.com/scrapy/index.htm

## 2)Newspaper:

Newspaper is a Python module used for extracting and parsing newspaper articles. Newspaper use advance algorithms with web scraping to extract all the useful text from a website. It works amazingly well on online newspapers websites. Since it use web scraping too many request to a newspaper website may lead to blocking, so use it accordingly.
### Features:
- Multi-threaded article download framework
- News url identification
- Text extraction from html
- Top image extraction from html
- All image extraction from html
- Keyword extraction from text
- Summary extraction from text
- Author extraction from text
- Google trending terms extraction
- Works in 10+ languages (English, Chinese, German, Arabic, …)
### References:
https://newspaper.readthedocs.io/en/latest
https://www.geeksforgeeks.org/newspaper-article-scraping-curation-python

## 3)News-please:
news-please is an open source, easy-to-use news crawler that extracts structured information from almost any news website. It can recursively follow internal hyperlinks and read RSS feeds to fetch both most recent and also old, archived articles. You only need to provide the root URL of the news website to crawl it completely. news-please combines the power of multiple state-of-the-art libraries and tools, such as scrapy, Newspaper, and readability. news-please also features a library mode, which allows Python developers to use the crawling and extraction functionality within their own program.      
### Features:
- works out of the box: install with pip, add URLs of your pages, run :-)
- run news-please conveniently using its CLI mode
- use it as a library within your own software
- extract articles from commoncrawl.org's news archive
### References:
https://github.com/fhamborg/news-please

## 4)Webcorpus:

webcorpus is an end-to-end tool used to crawl and generate datasets from the crawled data. It can be used to generate monolingual corpora and has various processors to create labelled datasets automatically. webcorpus is particulary suited for low-resource languages which need automated methods for creating large-scale datasets.




### Features: 
- This project has been used to generate IndicCorp, a large-scale corpora for Indic languages, and some datasets for IndicGLUE.
### References:
https://github.com/divkakwani/webcorpus

## 5)PyGoogleNews:

PyGoogleNews, created by the NewsCatcher Team, acts like a Python wrapper for Google News or an unofficial Google News API. It is based on one simple trick: it exploits a lightweight Google News RSS feed.
### Features:
It can fetch
- Top stories
- Topic-related news feeds
- Geolocation specific news feed
- An extensive query-based search feed
### References:
https://newscatcherapi.com/blog/python-web-scraping-libraries-to-mine-news-data
 
## 6)NewsCatcher:
 
This one is another open-source library created by our team that can be used in DIY projects. It’s a simple Python web scraping library that can be used for scraping news articles from almost any news website. It also enables you to gather details related to a news website. Let’s elaborate on this with the help of some examples and code.
### Features:
It can fetch data points from the news websites like:
- Title
- Link
- Authors
- Tags
- Date
- Summary
- Content
- Link for Comments
- Post_id
### References:
https://newscatcherapi.com/blog/python-web-scraping-libraries-to-mine-news-data
## 7)Feedparser:
 
The FeedParser Python library runs on Python3.6 or later and can be used to parse syndicated feeds.
### Features:
- it can parse RSS or Atom feeds and provide you with the information in the form of easy-to-understand data points. It acts as a news scraper and we can use it to mine news data from RSS feeds of different news websites.
### References:
https://newscatcherapi.com/blog/python-web-scraping-libraries-to-mine-news-data
