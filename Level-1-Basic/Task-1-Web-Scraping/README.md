# Task 1: Data Collection and Web Scraping

## Project Overview

This project focuses on automated data collection through web scraping. A Python-based web scraper was developed to collect book data from the **Books to Scrape** website.

The scraper navigates through all available catalogue pages, extracts relevant book information, performs basic data transformation, and exports the final dataset as a structured CSV file for further analysis.

**Data Source:** [Books to Scrape](https://books.toscrape.com/index.html)

---

## Objective

The objective of this project was to:

- Collect structured data from a multi-page website.
- Automate navigation across all catalogue pages.
- Extract relevant information for each book.
- Clean and transform selected fields.
- Store the collected data in a structured format for future analysis.

---

## Data Collected

The scraper extracts the following information for each book:

- Book Title
- Price
- Star Rating
- Availability

The scraper processes all **50 pages** of the catalogue and compiles the collected information into a single dataset.

---

## Methodology

The project follows the following workflow:

1. Send HTTP requests to retrieve webpage content.
2. Parse HTML content using BeautifulSoup.
3. Identify and extract relevant book information.
4. Iterate through all catalogue pages.
5. Clean extracted values, including price formatting.
6. Convert textual star ratings into numerical values.
7. Store the final dataset in CSV format.

---

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas

---

## Project Structure

```text
Task-1-Web-Scraping/
│
├── data/
│   └── books_cleaned.csv
│
├── notebook/
│   └── web_scraper.ipynb
│
└── README.md
```
## Output

The final output of the project is a cleaned dataset containing the books collected from the website:

- data/books_cleaned.csv

The notebook containing the complete scraping process can be found in:

- notebook/web_scraper.ipynb

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Web scraping and automated data collection.
- Working with HTML page structures.
- Extracting structured information from unstructured web content.
- Handling multi-page web scraping.
- Cleaning and transforming scraped data.
- Exporting data for further analysis.
