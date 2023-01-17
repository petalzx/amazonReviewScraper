# amazonReviewScraper

This is a web scraper that collects Amazon review data for machine learning projects such as sentiment analysis. The program is built with global commands, allowing it to collect review data from any product on Amazon. It collects the following information for approximately 160 reviews per product search:

* Product name
* Price
* ASIN (Amazon Standard Identification Number)
* Review title
* Review text
* Review rating

The program collects the relevant information and stores it in a dataframe. Using the last code cell of the program, you can download this dataframe as a csv file.

The program was developed using Jupyter Notebook and utilizes the following libraries: BeautifulSoup for web scraping, requests for sending HTTP requests, and pandas for data manipulation. 

# Installation

Install the file titled "amazonReviewScaper.ipynb" and run all of the code cells within the file to start collecting reviews. If you want to change the product being searched, change the value of the variable "search_query".

# Contributing 

petalzx - Developer
