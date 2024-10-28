

# Web Scraping Script for Globus Online KG

This project is a Python-based web scraping script designed to extract product data from the Globus Online KG website, specifically from the groceries section. The script uses `BeautifulSoup` for HTML parsing and `requests` for fetching the webpage content.

## Features

- Extracts product names, prices, and measurement units from the grocery listings.
- Processes and cleans data to provide structured output for further analysis or storage.
- Can be adapted for different categories or pages on the website.

## Requirements

To run this script, you need the following Python libraries:

- `requests`: For fetching web content
- `BeautifulSoup` (from `bs4`): For parsing HTML

To install the required packages, run:
```bash
pip install requests beautifulsoup4
```

## Setup and Usage

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/globus-scraper.git
   cd globus-scraper
   ```

2. **Run the script**:
   - Simply execute the script to scrape data from the specific page:
     ```bash
     python scraper.py
     ```
   - The script fetches and parses data, outputting product names, prices, and measurement units.

3. **Code Structure**:
   - `requests` is used to fetch the HTML content.
   - `BeautifulSoup` parses the HTML to locate product information within specific tags.
   - Data is stored in lists for easy access and further processing.

## Example Output

The script collects and organizes data as follows:
```plaintext
Product Name: Rice
Price: 500 KGS
Measurement: kg
```


