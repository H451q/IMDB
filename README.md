# Oscar-Winning Films Data Scraper

## Overview
This Python script scrapes information about Academy Award-winning films from Wikipedia, extracting details such as film names, years, awards, and nominations.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- BeautifulSoup
- requests
- re (regular expressions)

## Key Features
- Web scraping from Wikipedia's list of Academy Award-winning films
- Extracts film details into a structured pandas DataFrame
- Handles HTML parsing and text extraction

## How It Works
1. Sends a request to the Wikipedia page for Oscar-winning films
2. Uses BeautifulSoup to parse the HTML content
3. Extracts film, year, award, and nomination information
4. Creates a pandas DataFrame with the scraped data


## Data Columns
- Film: Name of the film
- Year: Year of the award
- Award: Specific Oscar award won
- Nomination: Nomination details

## Limitations
- Scrapes only the first 1373 entries
- Relies on the specific structure of the Wikipedia page
- May require updates if the webpage structure changes

## Potential Improvements
- Add error handling for web scraping
- Implement more robust data cleaning
- Create functions for more flexible data extraction

## License
Open-source project. Feel free to use and modify with attribution.

## Note
Web scraping should be done responsibly and in compliance with the website's terms of service.
