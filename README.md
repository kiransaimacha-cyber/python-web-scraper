# python-web-scraper
A Python script that extracts product data from an e-commerce site and saves it to a CSV file.
# E-commerce Product Scraper

## 📌 Overview
This Python script is designed to extract product data from an e-commerce website and save it into a clean, structured CSV file. It is built to handle pagination and extract specific data points like product name, price, and availability.

## ⚙️ Features
*   Scrapes product titles and prices.
*   Handles multiple pages of results.
*   Cleans the data (removes extra spaces/symbols).
*   Exports the final dataset to `products.csv`.

## 🛠️ Requirements
To run this script, you need Python 3 installed. You will also need the following libraries:
*   `requests`
*   `beautifulsoup4`
*   `pandas`

You can install them using:
`pip install requests beautifulsoup4 pandas`

## 🚀 How to Use
1. Clone this repository.
2. Open your terminal and navigate to the project folder.
3. Run the script:
   `python scraper.py`
4. Check the folder for the generated `products.csv` file.

## ⚠️ Disclaimer
This script is for educational purposes. Always ensure you have permission to scrape a website and respect their `robots.txt` file.
