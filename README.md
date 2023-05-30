# WebCrawler


This simple web crawler was created in Python using the requests and beautifulsoup modules. 

It downloads and stores the HTML of the visited sites to the local file system after crawling a given URL to a certain depth. 

The crawler handles HTTP response codes 200, 301, 403, 404, and 500, and employs a session object to control cookies.

## Features

- Depth-crawls a provided URL to a specified depth.
- Downloads and stores the HTML of the pages that are browsed.
- Handles the 200, 301, 403, 404, and 500 HTTP response codes.
- Manages cookies using a session object.

## Requirements

This project requires Python 3 and the following Python libraries installed:

- [BeautifulSoup](https://pypi.org/project/beautifulsoup4/)
- [Requests](https://pypi.org/project/requests/)



