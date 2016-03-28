## Yale Energy Dataset

This project revolves around the monthly reports on the environmental impact of Yale University produced by the Office of Sustainability and Yale Facilities. Open data transparency can help members of the community to better understand the impact of their energy choices.

## Contents

- `energy_collection.ipynb` - iPython notebook for gathering and cleaning the data
    - **Deprecated** as of March 2016 - the energy explorer server only accepts
    requests from the site host, so the current scraping method will not work.
    Need to rewrite to download and parse the CSVs manually. 
- Full dataset as a CSV, current as of December 2015
    - `buildings_data.csv` - All energy usage records
    - `buildings_demographics.csv` - Details about each building

## Initiatives
- Carbon Report Card for Buildings
- Campus Footprint
- The Green Tyng Cup

All data is collected from the public [Yale University Energy Explorer](http://java.facilities.yale.edu/energy/)

Other campus green energy projects can be found [here](www.cameronyick.us/yalegreen).

## Todo
- Add documentation on data limitations 
- Improve documentation in the iPython notebook, and improve robustness of the scraping/merging code 
- Document fields of each dataset
- Directions for setting up ipython environment / notebook dependencies