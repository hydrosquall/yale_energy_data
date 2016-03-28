## Cleanup Notes
Date: 3/27/2016

Scraping script returns 500 Server Error, response stored in Postman, so last 
valid scrape is July 2010 through December 2015

Cleaning up the building demographics data: buildings are listed up to THREE 
times, duplication is in the CATEGORY column. 
- Served by CPP or SPP
- Served by SPP
- Academic & Admin / (usage categories)

Filtered out Power Plants, Served by CPP, Served by SPP, CPP or SPP, and WPP

Removed 5 duplicate rows that were in Not Served by Yale Plants / AND in 
west campus

The key we're searching with is Facid, not buildingID

Locations with 0 lat and longitude? Perhaps closed.

Left with 319 buildings with valid data

## Cleaning the USAGE dataset
- Not every building submits data every month, some are missing many entries
- Some months submit multiple times per month

So as not to compare apples to oranges, we'll focus on the COMBINED datatype
// 

// Who uses Diesel Energy?
Sterling and Central Power Plant use Diesel Fuel (in Gallons) every month
162k gallons, 114 gallons


Cogeneration or combined heat and power (CHP) is the use of a heat engine or 
power station to generate electricity and useful heat at the same time

Notice that some buildings hadn't been recategorized

Note some buildings have been RAZED or merged with other buildings