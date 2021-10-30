# Crime in Atlanta, GA, 2009-Sept. 2021
#### Team members: Antoine Perrymon, Wesley Watkins, Cornelia Miller, Chineze Okpala, Anthony Ndungu, AJ Lamar III, Evan Mickler, Beverly Phillips
## Motivation & Summary
The news media has given the impression that crime has increased over the last year during the pandemic, but how has crime trended over time? 
#### Data sources: 
- Atlanta Police Department Data (2009 - SEP-2021) https://www.atlantapd.org/i-want-to/crime-data-downloads
- Racial and geographic data gathered from 2020 Census via IPUMS-NHGIS https://www.nhgis.org/
- Google maps API https://developers.google.com/maps
- Openweatherapi https://openweathermap.org/api
- Covid data from the Georgia department of public health and the CDC https://dph.georgia.gov/covid-19-daily-status-report
- Georgia Department of Labor, Georgia Labor Market Explorer (2009-Sept 2021) https://explorer.gdol.ga.gov/vosnet/Default.aspx
## Data Cleanup and Exploration
- Normalized crime data files
- Removed all non-date values. 
- Removed all dates outside of scope of analysis (January 2009 - September 2021)
- Created year/month/day columns. 
- Merged Crime data with other data sets on one or both of these columns. 

Complete analysis can be found in the powerpoint presentation: Analysis of Crime in Atlanta_GA.pptx
