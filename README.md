# Bluedart-Courier-Tracking
An API based access for Bluedart couriers. You can track postage rates, pin code finder, track parcels, e.t.c through this. This repository is maintained by individual developers. You can commit changes and push them. We will approve and merge them in case they are helpful commits.

##What is Bluedart

Bluedart.com is the official website of a leading courier service based in South East Asia. [Bluedart surface courier tracking page](http://www.bluedarttrackings.in/) is a direct and straight forward way to track your couriers and packages for free online. However, it cannot be directly embbeded or consumed as it doesn't offer any Public API.

We are using screen scraping techniques to fetch tracking status results, postage rates and other useful information. This information can be formatted based on your liking.


##Tool Used

**Scrapy:** [Scrapy](http://scrapy.org/) is one of the best Python scraper libraries out there.

**Beautiful Soup**: Beautiful Soup is a great library to parse HTML and XML files. It can extract useful data from the clutter of information. We have used this awesome Python library for parsing of data such as postal codes, services charge, weight to cost calculator, e.t.c.

**API End Points**: They have an official API which provides end points for general public to consume. But this has not been integrated since we are using simple screen scraping techniques. 

##Terms of Usage

Since there isn't any fair usage policy defined, you must contact Bluedart team and request permission before using this in commercial projects. You can use it for free as long as it is a 'Not for Profit' project.

We appreciate your feedback and don't forget to report issues or bugs you may find in the way.
