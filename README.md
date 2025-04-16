

---

# Python Web Scraper & Data Aggregator

This project scrapes the latest 10 job listings from [vacancymail.co.zw/jobs](https://vacancymail.co.zw/jobs/) and saves the extracted data (Job Title, Company, Location, Expiry Date, Job Description) into a CSV file. It also supports automated scheduling and includes basic error handling and logging.

## Requirements

- Python 3.x
- Libraries: `requests`, `beautifulsoup4`, `pandas`, `schedule`

Install dependencies with:

```bash
pip install requests beautifulsoup4 pandas schedule
```

## Usage

1. Run the scraper manually:

   ```bash
   python web_scraper.py
   ```

2. Schedule the script using the built-in scheduling (or set up a cron/task scheduler).

## How It Works

- **Scraping:** Retrieves job data from the website using HTTP requests and parses HTML with BeautifulSoup.
- **Processing:** Cleans and organizes data with pandas.
- **Output:** Saves data in `scraped_data.csv`.
- **Logging:** Captures errors and key events for troubleshooting.

## Project Structure

```
WebScraperProject/
├── web_scraper.py     # Main script
├── scraped_data.csv   # Output file
└── README.md          # This file
```

--- 
