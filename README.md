# Data2
## Data 2 Knowledge check requirements
Pull in data from an API. Here's a list of public APIs that don't require Auth keys, though if you have another API you want to use feel free: https://apipheny.io/free-api/
* Find and print TWO descriptive statistics about your data. This can be absolutely anything, from the mean() or sum() of a column to the number of different categories, to the number of null values in a column. We just want to see two pieces of information.
* Write a query in Pandas to select a particular set of your data. You can use a mask or with .query(), but we want you to pull out a subset based on any parameter you like. This could be "show me every row where HTTPS=False" or anything else.
* Select and print the SECOND AND THIRD columns of your data frame.
* Select and print the FIRST 4 rows of you data frame.

## API URLS to Worldbank to pull Literacy and GDP data for all years 2010-2020
"http://api.worldbank.org/v2/country/All/indicator/SE.ADT.LITR.ZS?format=json&date=2010:2020"

"http://api.worldbank.org/v2/country/All/indicator/NY.GDP.PCAP.CD?format=json&date=2010:2020"
