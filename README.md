# Web Scraping with Python IMDB

## Introduction
In this repository we will be scraping the IMDB website to get all the movies from the year 2020. We will be using the BeautifulSoup library to scrape the website. We will be using the requests library to get the HTML content of the website. We will be using the pandas library to store the data in a CSV file.

## Requirements
- scrapy
- python3

## Installation
- Clone the repository
- Install the requirements
- Run the command `scrapy crawl "movies-released-in-2020" -O ../datasets/dataset.json`