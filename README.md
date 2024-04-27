# Dev Job Scraper

### -- Project Status: [Active] [Open]

### Project Intro <-> Objective

Automate the collection of job leads. This script is designed to scrape job listings from LinkedIn without the need to access the LinkedIn API or log into an account.

### Project Description

This is a web-scraper that side-steps the login step typically required by the LinkedIn API. Using this method can produce A LOT of requests; in doing so, you will most likely encounter "rate limiting" from the LinkedIn server.

### Installation

The notebook requires the following libraries and/or dependencies:

- 'Requests' library to perform HTTP requests without logging in.
- 'BS4' (BeautifulSoup4) for parsing HTML pages.
- 'Logging' for debugging and tracking the scraping process.
- Concurrency implemented with ThreadPoolExecutor for faster scraping.

### Usage

Add your search criteria for title, location & max_pages:

```
title = "Machine Learning"
location = "California"
max_pages = 1000
```

#### Data Cleaning

- Uses 'Pandas' for data manipulation and cleaning.
- Consolidating process:
  - Automates the compilation of CSVs collected from each scrape into a consolidated dataset.

### Areas of Improvement for this project

- Enhance error handling and resilience against website changes.
- Increase the scope of data extraction to include more detailed job metrics.
- Improve the efficiency of the data consolidation process.

### Contributing Qwasar Members

| Name                                          | Discord Handle    |
| --------------------------------------------- | ----------------- |
| [John Jepsen](https://github.com/John-Jepsen) | John Jepsen#8888  |
| ---------                                     | ----------------- |

### Contact

For any further questions, you can contact [John Jepsen](https://github.com/John-Jepsen) on Discord at John Jepsen#8888 or open an issue in this repository.

---
# linkedin_scrapper
