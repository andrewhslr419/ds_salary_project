#Data-Science-Project

Glassdoor.com scraper and data science project

I scraped Glassdoor.com to collect and analyze company information and salary offers for data science jobs accross the country. Here is the process I used to collect it.

Web scraping is a method for collecting information from web pages and is a fun and practicle use of python. The challenges are Glassdoor’s library provides a limited number of data points. Glassdoor doesn’t allow you to scrape jobs or reviews. You only get to scrape companies, which didn't have value for me here. In this project, I will show you how I collected and cleaned data with selenium and sypder then preformed exploritory data analysis with Jupyter Notebook.

Selenium specifically was used because Glassdoor renders its content with Javascript. Using a simple get request to the webpage would only return the visible content and I needed to go much deeper than that.
data science salary analysis from glassdoor
