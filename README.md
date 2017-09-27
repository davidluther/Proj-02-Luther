# Proj-02-Luther
Web Scraping and Linear Regression
---

## Overview
The intial idea is to create a model that tries to predict the expected delay for arriving flights at a particular airport. I will start on the smaller side, with my hometown airport of TVC, and try to scrape from one (or more) of the popular flight database sites, going back as far as I can. Possible features include, but are not limited to:

1. Scheduled arrival time
1. Day of week
1. Airline
1. Airport of origin
1. Distance from origin to destination
1. Month of year
1. Day of year
1. Local weather

In this case, the MVP will focus on one airline with the target being expected delay (minutes) and a single feature, day of the week.

If this runs successfully, I will A) add in other features, roughly in the order listed, and/or B) create a model for each airline serving the airport.

I will focus only on commercial flights, filtering out all non-com flights by using RE to catch N-numbers.

## Data Sources
Potential sites for scraping:
* [FlightAware](https://flightaware.com/)
* [FlightStats](http://www.flightstats.com/go/Home/home.do)
* [Flight Data Services](https://www.flightdataservices.com/)
* [Flightradar24](https://www.flightradar24.com/data/)

