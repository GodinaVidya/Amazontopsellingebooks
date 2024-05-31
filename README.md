# Amazon Top-Selling E-Books Analysis

## Project Overview
This project involves scraping data of Amazon top-selling e-books from Amazon Kindle, cleaning and combining the data using Power Query, and performing data visualization using Power BI. The final report includes an analysis of revenue vs. profit by budget, customer reviews, and sales profits of each book.

## Data Collection
The data was collected using Python libraries:
- BeautifulSoup
- Numpy
- Pandas

## Data Cleaning and Combining
The data cleaning and combining were performed using Power Query in Excel. Random data columns were added for further analysis.

## Data Visualization
The data visualization was created using Power BI. The report includes:
- Revenue vs. Profit Analysis by Budget
- Customer Reviews Analysis
- Sales Profits of Each Book

## Files in Repository
- `data/amazon_ebooks_data.xlsx`: The cleaned and combined dataset.
- `src/scrape_data.py`: Python script for data scraping.
- `src/data_cleaning.py`: Python script for data cleaning.
- `src/data_combining.py`: Python script for data combining.
- `reports/power_bi_report.pbix`: Power BI report file.
- `README.md`: Project documentation.
- `.gitignore`: Git ignore file for Python.
- `LICENSE`: Project license.

## How to Run the Code
1. Clone the repository.
   ```bash
   git clone https://github.com/godinavidya/amazon-top-selling-ebooks-analysis.git
   cd amazon-top-selling-ebooks-analysis
