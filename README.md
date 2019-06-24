# spd-crimes-vs-villages
## Did this change affect crime rates?
SPD crime data comparison before-after visualization and stats for specific beat compared to city as a whole.

#### What is it?
Designed to look at impact of tiny house villages on neighborhood where they're built, but may be used for other before-after comparisons of SPD reports at a beat level - location data is only provided at beat level, not lat-long to provide privacy and allow more reports to be published (95% with beat vs. 40% with lat-long).

#### Limitations
SPD beats have changed repeatedly over the years. Data could be inaccurate (and should raise a warning) if range spans two or more of the following date ranges:
- < 2008
- 2008-2014
- 2015-2017
- 2018-2019

See https://data.seattle.gov/Public-Safety/Seattle-Police-Department-Beats/nnxn-434b for more information on beats

If you want to compare something across two or more date ranges, you will need to use crime data by precinct, which will be less granular. This data from 2008 and forward is at https://data.seattle.gov/Public-Safety/Seattle-Crime-Stats-by-Police-Precinct-2008-Presen/3xqu-vnum.
