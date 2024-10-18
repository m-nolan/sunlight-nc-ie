# NC Independent Expenditure Scraper
Michael Nolan

2024-10-27

# Overview
This repo contains a script that downloads independent expenditure records from the North Carolina Board of Elections website: https://www.ncsbe.gov/

These documents are public and freely available. This code automates the process of downloading and saving all IE filings made in a given year into a single CSV file.

# Dependencies:
- python

### python packages:
- pandas
- selenium
- tqdm

# Installation
To run the code, simply clone the repo:
- `git clone git@github.com:m-nolan/sunlight-nc-ie.git`

Change directories to where you cloned the repo:
- `cd sunlight-nc-ie`

And run the script as follows:
- `python nc-ie-scraper.py <year>`
Where you replace `<year>` with the year you would like to grab filings from. For example: `python nc-ie-scraper.py 2021`.
