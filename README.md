# Myntra Web Scraping Script

## Overview

This Python script, named "myntra_lv.ipynb," is designed to scrape product data from the Myntra website, specifically focusing on a collection of laundry bags. It utilizes the Selenium library to automate a web browser (Chrome) and extract information about each product on multiple pages of the collection. The scraped data is then stored in a Pandas DataFrame for further analysis or usage.

## Prerequisites

Before running the script, ensure you have the following:

1. **Python Environment**: Make sure you have a Python environment set up with the necessary packages installed. You can use Python 3.x for this script.

2. **Selenium**: Install the Selenium library using `pip` if you haven't already:

   ```
   pip install selenium
   ```

3. **Chrome WebDriver**: Download the appropriate version of the Chrome WebDriver compatible with your Chrome browser. Set the path to the WebDriver in the script's `DRIVER_FILE_PATH` variable.

4. **User Agents**: The script uses a list of user agents for browser emulation. You can modify the `USER_AGENT_LIST` variable to include your own user agents if needed.

## Usage

1. Open the "myntra_lv.ipynb" script in a Jupyter Notebook or any compatible Python environment.

2. Configure the script as needed:
   - Set `headless_flag` to `True` if you want to run the browser in headless mode (no GUI). Set it to `False` for a visible browser.
   - Modify the `USER_AGENT_LIST` if you want to use specific user agents for browser emulation.
   - Adjust the `collection_url` variable to target the specific Myntra collection you are interested in.

3. Run the script, and it will start scraping data from Myntra's website.

4. The script will print information about the products as it scrapes them, including the number of cards on each page.

5. Once the scraping is complete, the data will be stored in a Pandas DataFrame (`df`) for further analysis.

6. The script will automatically close the Chrome browser.

## Important Notes

- Web scraping should be conducted responsibly and in compliance with the terms of service of the website you are scraping. Ensure that your scraping activities are legal and ethical.

- Websites may change their structure or have rate limits in place, which could affect the script's functionality. Periodic updates to the script may be required.

- The script is designed for educational purposes and as a starting point for web scraping projects. Modify it as needed to suit your specific requirements.# myntra-selenium-scraper
