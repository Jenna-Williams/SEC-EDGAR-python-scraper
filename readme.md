# SEC - EDGAR | Web Scraper

* This project will scrape and return fundamental financial data.
* In the current state it is fully functional, utilizing Python and the Scrapy library.
* Data exists from 2011.
* The labeling script determines document type and stores in a parsed folder.
* The aggregation script is in the early stages and will be further developed.

## Getting Started
1. Copy the repository and Install requirement.txt using pip
2. To scrape data run scraper.py and pass symbols of companies you want to scrape and year
      ```
         python scrape.py
      ```.
        
   The scraped files are stored in scraped folder 

   To label all scraped files just run 
      ```
         label.py
      ```.

## Contribution
The original dev is seeking conributiors to improve efficiency, structure and functionality.

## License

This project is licensed under the terms of the MIT license.

"# SEC-EDGAR-python-scraper" 

# Additional Features
* I plan to expand this project by adding additional data sources, beyond the EDGAR database.

## A note 
I have a second degree in accounting and currently sitting for the CPA Exams (halfway there). 

