Amazon Product Scraper is a Python-based tool designed to extract product information such as titles, prices, ratings, reviews, and availability from Amazon product listings. This tool is helpful for gathering data for analysis, competitive pricing, and market research.

Features
Extract Product Details: Get product titles, descriptions, and other key details.
Price Collection: Collect product prices for tracking and analysis.
Review & Rating Retrieval: Retrieve customer reviews and ratings to assess product popularity.
Availability Status: Check if products are currently available or out of stock.
Requirements
Python 3.x
Required Libraries: requests, BeautifulSoup4, pandas, numpy
Setup
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/amazon-scraper.git
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Set your user agent in the HEADERS section of the code to prevent being blocked by Amazon.
Usage
Open amazon_scraper.py.
Set the Amazon product URL or search URL you want to scrape.
Run the script:
bash
Copy code
python amazon_scraper.py
The scraped data will be saved as a .csv file in the project directory.
Functions
get_title(): Extracts the product title.
get_price(): Extracts the product price.
get_rating(): Extracts the product rating.
get_review_count(): Extracts the number of customer reviews.
get_availability(): Extracts the product's availability status.
Notes
Amazon's Terms of Service prohibit data scraping in certain contexts. Use this tool responsibly and consider alternatives like Amazon's official API for permitted data extraction.
Use proxies or rotate user agents to avoid getting blocked by Amazon’s anti-scraping measures.
License
This project is licensed under the MIT License. See LICENSE for details.

