WEB SCRAPPING - CARS

📌 Project Overview

This mini-project focuses on web scraping used Audi car listings from Cars24 across multiple cities.

The scraper extracts important details like year of manufacture, kilometers driven, fuel type, transmission, price, registration location, and number of owners.

By completing this project, I gain hands-on experience in:

Web scraping with Selenium, BeautifulSoup, and Requests

Data cleaning and structuring

Automating city-wise scraping

Exporting structured data for analysis

🎯 Features

Scrapes Audi cars only

Covers multiple locations (Mumbai, Chennai, Bangalore)

Extracts:

Year of Manufacture

Kilometers Driven

Fuel Type

Transmission

Price

Location

Number of Owners

Handles dynamic loading with infinite scroll

Saves data into CSV/Excel for easy analysis

🛠️ Tech Stack

Python 3

Libraries:

Selenium (for dynamic scrolling)

BeautifulSoup4 (for parsing HTML)

Requests (for fetching detail pages)

Pandas (for saving structured data)

1. Data Collection
  link : https://www.cars24.com/buy-used-cars/

3. Create Virtual Environment
python -m venv .venv
.venv\Scripts\activate      # for Windows

4. Install Requirements
pip install -r requirements.txt

5. Run the Scraper
python scraper.py


Data will be saved into a CSV/Excel file for analysis.

📂 Output Example
Brand	Model	Year	KM Driven	Fuel	Transmission	Price	Location	Owners
Audi	A6	2013	82,000 km	Diesel	Auto	₹12.97 Lakh	Mumbai	1st Owner
Audi	Q3	2016	65,000 km	Petrol	Manual	₹15.5 Lakh	Chennai	2nd Owner
📌 Notes

Cars24 may block scraping if requests are too frequent — use delays responsibly.

Owners info is extracted from detail pages, so network delays may occur.

Use the .gitignore file to avoid committing unwanted files (like __pycache__, .venv, or Selenium drivers).
