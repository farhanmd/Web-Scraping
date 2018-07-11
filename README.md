# Web-Scraping Project using Scrapy Framework

In order to scrape the website, I have used Scrapy. In short, Scrapy is a framework built to build web scrapers more easily and relieve the pain of maintaining them. Basically, it allows us to focus on the data extraction using CSS selectors and choosing XPath expressions and less on the intricate internals of how spiders are supposed to work. 

Output files:
The data outputted in this project should is present in the MonthDay_year.csv file. The individual campaigns scraped will vary as the website is constantly updated. Also it is possible there will be spaces between each individual campaign as excel is interpreting the csv file. This is a small dataset that was scraped from a single campaign. 

I have created a final dataset performing web scraping on 450 campaigns(it was made by changing npages = 2 to npages = 450 and adding download_delay = 2 in the spider file), The file is called 450PagesScraper.csv (it is a large file).

Hope this helps!!
