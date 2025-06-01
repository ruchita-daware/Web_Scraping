# Web_Scraping
# Quote Web Scraping

A simple web scraping project that extracts quotes from the website [Quotes to Scrape](http://quotes.toscrape.com/). This project demonstrates how to use Python and BeautifulSoup to collect data from web pages.

## 📌 Features

- Scrapes quotes, authors, and tags
- Saves data into a CSV file
- Handles pagination automatically
- Clean and easy-to-understand code

## 📂 Project Structure

quote-web-scraping/
│
├── quote_scraper.py # Main scraping script
├── requirements.txt # Python dependencies
├── output.csv # Output CSV file with scraped data
└── README.md # Project documentation

## 🚀 Technologies Used

- Python 3.
- BeautifulSoup (bs4)
- requests
- pandas (optional for CSV handling)

The script will:

Visit each page on the site

Extract quotes, authors, and tags

Save the data into output.csv

Example Output
Quote	                               Author	                 Tags
“The world as we have created it…”	Albert Einstein	change, deep-thoughts

1. **Clone the repository**
   git clone https://github.com/yourusername/quote-web-scraping.git
   
