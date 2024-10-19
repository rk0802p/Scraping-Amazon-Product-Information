# Scraping-Amazon-Product-Information
This Python script allows you to scrape product details from Amazon using `BeautifulSoup4`. The script retrieves details such as the product name, price, rating, and more, depending on the webpage structure.

## Features
- Scrapes product name, price, and ratings from Amazon product pages.
- Uses `requests` to fetch the webpage content.
- Utilizes `BeautifulSoup4` to parse the HTML content.
- Saves the scraped data to a CSV file.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- `requests` module
- `beautifulsoup4` module
- `lxml` parser (optional but recommended for faster parsing)

### Installation

You can install the required libraries by running:

```bash
pip install requests beautifulsoup4 lxml

### Usage

- Clone this repository or download the script.

- Open the script in a text editor and update the URL variable with the  Amazon product page URL you want to scrape.

- Run the script in your terminal or command prompt:
