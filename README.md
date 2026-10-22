# Web Scraping Eye Care Project
# Eyewear Product Web Scraping

Python scrapers that collect eyeglasses product data from eyewear retail websites and save it as clean CSV and JSON files.

## What it does
- Loads product pages with Selenium (for content loaded by JavaScript) and parses them with BeautifulSoup.
- Extracts product details such as name, brand, and price.
- Exports results to CSV (for spreadsheets) and JSON (for other programs).

## Files
- `framesdirect.py` / `framesdirect.ipynb`: FramesDirect scraper
- `glassesusa.py` / `glassesusa.ipynb`: GlassesUSA scraper
- `*.csv`, `*.json`: sample output

## Tools
Python, Selenium, BeautifulSoup, requests, pandas

## How to run
pip install -r requirements.txt
python framesdirect.py

