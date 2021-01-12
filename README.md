# Scraping-projects-in-Python
Different scripts for scraping; currently holds one for Trustpilot and Boligportalen.

## Trustpilot script
Scrapes the Trustpilot site (in this case, the company AURA Energi) for all review entries. To get around that the URL is unique pr page - in contrast to the usual URL-construction, where page-URL is conveniently specified with page = 1 or 2 within the URL - a workaround was made to just access the link embedded in the "Next" button on the site.

### Prerequisites
Install the Python package bs4 with `python3.8 -m pip install -r trustpilotRequirements.txt`.

## Boligportalen script
Scrapes the BoligPortal site for the newest apartment entries and plays a sound when a new apartment below a given price point is found.

### Prerequisites 
Install the Python packages with `python3.8 -m pip install -r boligportalRequirements.txt`.

You need the Selenium WebDriver to run the program since it loads content with JS. There are many ways to install this, but I used `npm install phantomjs`. 
