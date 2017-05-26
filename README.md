# 990-scraper
Grab U.S. nonprofit tax information from the [ProPublica Nonprofit Explorer API](https://projects.propublica.org/nonprofits/api) and put it in a Google spreadsheet!

## What's in a 990?
Nonprofit corporations in the United States have to submit one of a few types of tax forms to the IRS each year, which are then made public. If their total revenue is over $200,000 in a year, they submit a [form 990](https://www.irs.gov/pub/irs-pdf/f990.pdf), if it is between $50,000 and $199,999, they submit a [form 990-ez](https://www.irs.gov/pub/irs-pdf/f990ez.pdf), and if it is under $50,000, they submit a [990-N (e-postcard)](https://www.irs.gov/charities-non-profits/annual-electronic-notice-form-990-n-for-small-organizations-what-to-report). The information obtained from these forms from 2011-2014 is what has been made available through the ProPublica Nonprofit Explorer API.

## What does this do?
If you have [a list of nonprofit organizations in a Google spreadsheet](https://docs.google.com/spreadsheets/d/1jwM-cYI1Ep9ZjNxGDjJXjqNkYA-f1ViyAH-Bv1tLvV4/edit#gid=0), this will loop through that list, use the API's Search Method to find the org's EIN number, then uses the API's Organization Method to find out whatever else you want to find out (e.g. total revenues, location, number of volunteers, etc). It then gently places all of that into your Google Spreadsheet. 

## Where is the project now?
Nowhere. plz help

## Tutorials
- [Useful code snippets for working with the ProPublica APIs](https://www.propublica.org/nerds/item/useful-gists)
- [Coding with Google Apps Script](http://www.benlcollins.com/spreadsheets/starting-gas/)
- [How to work with the Google Sheets API](https://developers.google.com/sheets/)

