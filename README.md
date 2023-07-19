# Module-11---Web-Scraping
Web scraping using splinter, pandas, and beautiful soup <br />
**Part 1: Scrape Titles and Preview Text from Mars News**

Used automated browsing to visit the Mars news siteLinks to an external site. Inspected the page to identify which elements to scrape.

Extracted the titles and preview text of the news articles that you scraped. Stored the scraping results in Python data structures as follows:

Stored each title-and-preview pair in a Python dictionary and, gave each dictionary two keys: title and preview. An example is the following:

{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
Store all the dictionaries in a Python list.

Printed the list in your notebook.

**Part 2: Scrape and Analyze Mars Weather Data**

Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site. Inspected the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Created a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, used Beautiful Soup here to continue sharpening my web scraping skills.

Assembled the scraped data into a Pandas DataFrame. The columns have the same headings as the table on the website.

Examined the data types that are currently associated with each column. I cast (or converted) the data to the appropriate datetime, int, or float data types.

Analyzed the dataset by using Pandas functions to answered the following questions:

1. How many months exist on Mars? 12
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
4. Plot the results as a bar chart.
5. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
6. Find the average daily atmospheric pressure of all the months.
7. Plot the results as a bar chart.
8. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
9. Consider how many days elapse on Earth in the time that Mars circles the Sun once.
10. Visually estimate the result by plotting the daily minimum temperature.
11. Export the DataFrame to a CSV file.
