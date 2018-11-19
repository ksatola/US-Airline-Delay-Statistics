# US Airline Delay Statistics

## Overview
The main objective of the project was to create a data visualization using Tableau that tells a story or highlights trends or patterns in a dataset. The main dataset used in the project contains information on the United States flight delays and performance in 2008 and comes from [RITA](http://stat-computing.org/dataexpo/2009/the-data.html). In the project, I have focused on highlighting general trends and patterns especially important from a passenger perspective, and factors minimizing risks related to delayed or cancelled flights.

The story has been published to [Tableau Public](https://public.tableau.com/profile/krzysztof5356#!/vizhome/fo008/Story1?publish=yes).

This project was completed as part of Udacity's [Data Analyst Nanodegree](https://eu.udacity.com/course/data-analyst-nanodegree--nd002) certification.

## Data Origin
- **2008.csv** - Main dataset downloaded from [RITA](http://stat-computing.org/dataexpo/2009/the-data.html)
- **Airports.csv** - Supplementary [file with airport names](http://stat-computing.org/dataexpo/2009/supplemental-data.html)
- **Carriers.csv** - Supplementary [file with carrier names](https://exploratory.io/data/kanaugust/9876993836892339)
- **Plane-data.csv** - Supplementary [file with plane manufacturers data](http://stat-computing.org/dataexpo/2009/supplemental-data.html)
- **FlighPaths2008.csv**, **FlighPaths2008_summary.csv** - Transformed **2008.csv** file to be rendered by Tableau in a way paths can be showed on a map (Dashboard7). Prepared by using [FlightPaths2008.ipynb](https://github.com/ksatola/US-Airline-Delay-Statistics/blob/master/FlightPaths2008.ipynb).
 
## Results
A set of insights into flight delays and cancellations in 2008 in the US as an [interactive, online Tableau presentation](https://public.tableau.com/profile/krzysztof5356#!/vizhome/fo008/Story1?publish=yes). A static, preview version is available in the [PDF format](https://github.com/ksatola/US-Airline-Delay-Statistics/blob/master/The%20US%20Flight%20Odyssey%202008.pdf).

## Tools
- Tableau Desktop
- Python, Jupyter Lab
- Libraries: pandas
