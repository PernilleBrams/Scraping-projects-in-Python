# TrustpilotScraper
This repo currently holds a script for scraping AURA Energi's Trustpilot site.

## Trustpilot script
Scrapes the Trustpilot site (in this case, the company AURA Energi) for all review entries. To get around that the URL is unique pr page - in contrast to the usual URL-construction, where page-URL is conveniently specified with page = 1 or 2 within the URL - a workaround was made to just access the link embedded in the "Next" button on the site.

### Prerequisites
Install the Python package bs4 with `python3.8 -m pip install -r trustpilotRequirements.txt`.
