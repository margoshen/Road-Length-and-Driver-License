# Road-Length-and-Driver-License

Introduction to Programming for Public Policy: Final Project Proposal

Road Length and Driver License

Yeung(Flora) Fu   12149109
Liming Shen  12144476

The Question

Our final project aims to investigate the interrelationship between the number of licensed drivers and the public road length across the 50 states and Washington, D.C, with a careful consideration into the changes in the nation’s  rural/urban density. This is motivated by the fact that the number of issued driver licenses differ significantly across the states. We first consider each state’s public road length as one of the factors that may affect the licensed drivers population. In fact, the longest state highways is observed in Texas (80,067 miles by 2009)  while the lowest is found in Hawaii (946 miles). However, as indicated by a U.S Census Bureau report of rural/urban population characteristics,  by 2010 the fraction of rural population by state ranges from  4.9% (California) to 61% (Maine and Vermont).
Therefore, the inconsistency between the distributions of state road length and state rural density leads us to consider a jointly effect of these two factors. In other words, the project would like to answer the question that whether the public road length, along with urban/rural population statistics, would influence people’s decision-making when applying for their driver licenses and thus the licensed drivers population, or vice versa.

Data

The data we will use to analyze the relationship between public road length and driver license are from State Transportation Statistics (STS) and Highway Statistics from U.S. Department of Transportation’s Federal Highway Administration. STS contains series of reports highlighting major federal databases and other national sources related to infrastructure, safety, freight movement and passenger travel, vehicles, economy and finance, and energy and the environment at state level. The Highway Statistics Series consists of annual analyzed statistical information and reports on motor fuel, motor vehicle registrations, driver licenses, highway user taxation, highway mileage, travel, and highway finance. Later, we will use the data from the United States Census Bureau to take into account the change in population and rural level for each individual state over a greater time period.
We will use two disjoint data for each year from 2005 to 2009 - Infrastructure:Public Road Length, Miles by Ownership and Passenger Travel:Licensed Drivers. The first step before our statistical analysis will be merging the two csv files for each year based on state level. Then to see the total and percentage change in population and urban land area over the larger 10-year period for each state, we will change the xls file of 2000 to 2010 Population and Area Change by 2010 Urbanized Area to a csv file, rearrange and group the columns by state. For conclusion of the final project, we will take the bigger trend of overall 10-year (2000-2010) population and urban area change into account, from the five-year (2005-2009) period within we will discuss on the possible correlation between public road length and the number of new driver license issued.

Infrastructure:Public Road Length, Miles by Ownership

For each year from 2005 to 2009, this data includes public road length in total for each state and the length that each owner possesses, from state highway agency, county, town, to other jurisdiction and federal agency.

Passenger Travel:Licensed Drivers

This data consists of number of licensed drivers, licensed drivers per registered vehicle, resident population, driving age population (16 and over), driver per 1,000 total resident population, as well as drivers per 1,000 driving age for each date from 2005 to 2009. Number of licensed drivers includes restricted drivers and graduated driver licenses.

2000 to 2010 Population and Area Change by 2010 Urbanized Area

This file contains total and percent change in population and land area for the 2010 Urbanized Areas(city, state) from 2000 to 2010. Area and population change can be the result of one or a combination of 1) internal growth, 2) new growth, and/or 3) the merger of adjacent urban territory formerly associated with an urban cluster.


Data Sources (with links)
State Transportation Statistics- https://www.rita.dot.gov/bts/publications/state_transportation_statistics

Public Road Length, Miles by Ownership: 2005 - https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2006/csv/table_01_06.csv
Licensed Drivers: 2005-
https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2006/csv/table_04_02.csv

Public Road Length, Miles by Ownership: 2006 -https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2007/csv/table_01_02.csv
 Licensed Drivers: 2006 - https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2007/csv/table_04_02.csv

Public Road Length, Miles by Ownership: 2007 - https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2008/csv/table_01_02.csv
Licensed Drivers: 2007 - https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2008/csv/table_04_02.csv

Public Road Length, Miles by Ownership: 2008- https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2009/csv/table_01_02.csv
Licensed Drivers: 2008- https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2009/csv/table_04_02.csv

Public Road Length, Miles by Ownership: 2009- https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2011/csv/table_01_02.csv
Licensed Drivers: 2009- https://www.rita.dot.gov/bts/sites/rita.dot.gov.bts/files/publications/state_transportation_statistics/state_transportation_statistics_2010/csv/table_04_02.csv

2000 to 2010 Population and Area Change by 2010 Urbanized Area
https://www.census.gov/geo/reference/ua/ualists_layout.html


Problems Encountered

Solutions

Guideline for getting our work
See Notebook and FinalProject.py
