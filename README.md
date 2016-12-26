# scrapy_tutorial
This is a simple tutorial of scrapy. We will learn how to crawl a web page with scrapy and python 3.

### Introduction
web scraping == web spidering == web crawling == programatically extracting data from web page 

-> It helps to get data from a site without official API.

### Prerequisites
    Python 3

*Install scrapy* 
>   pip install scrapy

*Create new directory*
>   mkdir scrapy_tutorial

*Create scraper.py*
>   touch scraper.py

```
import scrapy

class BrickSetSpider(scrapy.Spider):
    name = "brickset_spider"
    start_urls = ['http://brickset.com/sets/year-2016']
```

*Run spider*
>   scrapy runspider scraper.py

