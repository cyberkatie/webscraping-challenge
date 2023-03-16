# webscraping-challenge
Penn Data Science Bootcamp Module 11 Assignment


# Part 1: Scrape Titles and Preview Text from Mars News

* Used automated browsing to visit the Mars news siteLinks to an external site. Inspected the page to identify which elements to scrape.
* Created a Beautiful Soup object and used it to extract text elements from the website.
* Extracted the titles and preview text of the news articles that were scraped. Stored the scraping results in Python data structures
* Stored each title-and-preview pair in a Python dictionary and gave each dictionary two keys: title and preview

# Part 2: Scrape and Analyze Mars Weather Data

* Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspected the page to identify which elements to scrape.The URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
* Created a Beautiful Soup object and uses it to scrape the data in the HTML table. 
* Assembled the scraped data into a Pandas DataFrame. The columns have the same headings as the table on the website.
* Examined the data types that are currently associated with each column. Casted (or converted) the data to the appropriate datetime, int, or float data types where necessary.
* Analyzed the dataset by using Pandas functions to answer the following questions:
  * How many months exist on Mars?
  * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  * What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this:
  * Find the average minimum daily temperature for all of the months.
  * Plot the results as a bar chart.
  * Which months have the lowest and the highest atmospheric pressure on Mars? To answer this:
  * Find the average daily atmospheric pressure of all the months.
  * Plot the results as a bar chart.
  * About how many terrestrial (Earth) days exist in a Martian year?
* Export the DataFrame to a CSV file.
