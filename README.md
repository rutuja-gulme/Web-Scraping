# Web Scraping with BeautifulSoup

A Python web scraping project that extracts article information from a webpage, cleans the data, and exports it as a structured CSV dataset.

## Objective

To collect article information from a webpage, extract relevant fields, clean the data, and prepare it in a structured format for further analysis or reuse.

## Tools & Technologies

* Python
* Requests
* BeautifulSoup
* LXML
* Pandas

## Workflow

1. Fetch webpage content using Requests.
2. Parse the HTML using BeautifulSoup with the LXML parser.
3. Extract article information from the webpage.
4. Separate the publication date and article title.
5. Convert the date field into datetime format.
6. Check for missing values.
7. Store the cleaned data in a Pandas DataFrame.
8. Export the dataset as a CSV file.

## Output

The project extracted **500 article records** with the following fields:

* `date`
* `article_title`

The resulting dataset is available in `scraped_articles.csv`.

## Source

Student News Daily — Daily News Article Archive

## Responsible Scraping

* Check the website's Terms and Conditions before scraping.
* Avoid sending excessive requests.
* Use appropriate request timeouts.
* Respect the website's structure and resources.
