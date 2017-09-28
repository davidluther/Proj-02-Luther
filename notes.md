# Modeling Arrival Delay at TVC

## Potential Data Sources
* [FlightAware](https://flightaware.com/)
* [Flightradar24](https://www.flightradar24.com/data/)
* [FlightStats](https://www.flightstats.com/go/Home/home.do)
* [Bureau of Transportation Statistics](https://www.transtats.bts.gov/)
* [FlightView](https://www.flightview.com/)
* [OpenFlights](https://openflights.org/data.html)

#### FlightAware
Only caches records for one week, but offers historical data for purchase.

#### Flightradar24
Very little in the way of historical, at least at first glance!

#### FlightStats
Focused more on individual flights than airports. No direct access to historical data, but gives some dubious stats on delays. Offers 30 day trial account for APIs though.

#### BTS
Lots and lots available here, but it's rather impenetrable at first glance, and all .aspx. TVC keeps on coming up blank, but there are some decent records for DTW and other bigger ones. Try:
* https://www.transtats.bts.gov/ONTIME/Index.aspx – No TVC! But yes to DTW. Would have to use Selenium and then Soup.
* https://www.bts.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics – lots and lots of things
* https://www.transtats.bts.gov/databases.asp?Mode_ID=1&Mode_Desc=Aviation&Subject_ID2=0 – perhaps the richest mine from the above

#### FlightView
TVC taps their feed for site stats. Check back later, got a 500 Internal Server Error on first try.

#### OpenFlights
Not sure what exaclty this is...
