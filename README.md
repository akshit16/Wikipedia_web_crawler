# Wikipedia_web_crawler
A python script to crawl through various wikipedia pages,searches and extract the first link from the main body.

This script will work till the following condition has occured:

1) A target page has been reached Which in this script is this
2) The search has gone on suspiciously long(Default maximum count has been initialized to 25)
3) We have arrived at an article we have already seen

Framework Information:

Python 3.6.0
Beautiful Soup Library v4

Installation Steps:

Python 3.6.0 need to be installed 

Install the following libraries by running the below commands on command prompt:
pip3 install requests
pip3 install bs4
Steps Running the application
>>> python wikipediacrawler.py

References
Udacity Tutorial
Beautiful Soup v4-Python Library
Requests API
