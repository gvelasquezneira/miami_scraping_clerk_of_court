This repository contains a Python script designed to scrape case information from the Miami-Dade County Clerk of Courts website. The script logs into the website using a personal account, searches for cases using case numbers, extracts charges and case information and saves it to a CSV file.

Features
- Automated login to the Miami-Dade Clerk of Courts website. 
- Parses case numbers and inputs the keys. 
- Extracts case information
- Replaces empty data fields with "NA" for consistency.
- Output saved to a case.csv file with a header structure.

Required Libraries:
- selenium
- beautifulsoup4
- webdriver-manager
- csv

*Note: For the script to work you need to create an account for the Miami-Dade County Clerk of Courts website.
