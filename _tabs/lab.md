---
title: Lab Challenges
icon: fas fas fa-flask
order: 4
---

## Web Scraping Challenge

### 🚧 Challenges Faced
#### Understanding HTML structure of the webpage
- Initially, it was challenging to identify the correct HTML tags and classes needed to extract the hockey table data accurately.
#### Parsing nested elements with BeautifulSoup
- Extracting data row-by-row required careful navigation through <table>, <tr>, and <td> elements, which was not straightforward at first.
#### Handling inconsistent or unclean text data
- The extracted data contained extra whitespace and formatting issues that needed to be cleaned before storing in a structured format.
#### Building and populating a Pandas DataFrame dynamically
- Appending rows to the DataFrame during iteration required understanding indexing and ensuring data aligned with the correct columns.
#### Working with HTTP requests and page loading
Ensuring the webpage loaded correctly and returned valid content using the requests library required debugging when responses were not as expected.

---

### ✅ How I Solved Them
- Inspected the webpage using browser developer tools to identify the correct table structure and class names.
- Used find() and find_all() methods in BeautifulSoup to accurately locate and extract elements.
- Applied .text.strip() to clean and standardize the extracted data.
- Used .loc[] indexing in pandas to dynamically append rows to the DataFrame.
- Verified request responses and tested the scraping process step-by-step to ensure data was correctly retrieved.

---
### 🎯 Key Learnings
- Gained practical experience in web scraping using Python.
- Improved skills in HTML parsing and data extraction.
- Strengthened understanding of data cleaning and structuring with pandas.
- Learned how to automate data collection and export to CSV format.

---
