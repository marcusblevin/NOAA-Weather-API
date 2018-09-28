# NOAA-Weather-API

Connect to the NOAA weather API and poll for data form the available data sets based on zip code and begin/end date

## Getting Started

You must go to [NOAA's API](https://www.ncdc.noaa.gov/cdo-web/webservices/v2) page to obtain a token to connect. Review the API page for any additional detail.

## Running

Can be run locally or as part of a site. When page loads, initial requests will load the available data sets from NOAA and populate select list. 

Choose data set to view and enter zip code and begin/end date. The getData function will perform an async call to NOAA's API and display the result set
