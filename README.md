# Job Vacancy Web Scraper (Python Data Sourcing Pipeline)

## Project Overview
An automated web-scraping pipeline built with Python, Requests, BeautifulSoup, and Pandas. This project automates job vacancy data extraction for recruitment agencies, processing listing attributes into structured tabular CSV format to reduce candidate sourcing time.

## Tech Stack & Libraries
- Python 3
- BeautifulSoup4 (DOM Parsing)
- Requests (HTTP Network Calls)
- Pandas (Data Cleaning & Exploration)
- Matplotlib / Seaborn (Visual Analytics)

## Repository Contents
- `WebScraping.ipynb`: Complete Jupyter Notebook with code pipeline and EDA visualizations.
- `fake_jobs_data.csv`: Scraped output dataset containing 100 job records.

## Key Features & Architecture
- **Dynamic Request Management:** Includes browser user-agent headers to manage network requests safely.
- **Defensive Data Extraction:** Implements `try-except` guardrails to handle missing DOM attributes gracefully.
- **Export Pipeline:** Normalizes text fields and exports structured data to CSV.

## Key Findings
- Ingested 100 job entries with 0% missing value rate across primary fields.
- Automated data sourcing reduces job collection time from ~45 minutes manually to under 3 seconds programmatically.
