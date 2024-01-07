# Email web scraper

## Description

This Python script, `email.py`, is designed to scrape emails from websites. It takes a target URL as input and extracts email addresses from that URL and any associated links it finds on the same domain. The script uses the BeautifulSoup library for parsing HTML and the requests library for handling HTTP requests.

## Features

- Input a target URL to start the email scraping process.
- Scrape email addresses from the given URL and any related internal links.
- Limit the scraping to the first 25 URLs found (configurable).
- Handle various exceptions and errors gracefully.
- Output the found email addresses in the console.

## Requirements

- Python 3
- BeautifulSoup4
- requests

## Installation

First, ensure that Python 3 is installed on your system. Then, install the required packages using pip:

```bash
pip install beautifulsoup4 requests
```

## Usage

Run the script from the command line:

```bash
python email.py
```

Enter the target URL when prompted. The script will begin processing and output any email addresses it finds.

##Limitations

-The script is limited to scraping the first 25 URLs to avoid overloading the server. This limit can be adjusted in the script.
Only scans URLs within the same domain as the target URL.

-The effectiveness depends on the structure of the website and the presence of emails in accessible HTML content.
Disclaimer

This tool is for educational purposes only. Always seek permission before scraping websites, as unauthorized scraping may violate the terms of service of the website and local laws.
