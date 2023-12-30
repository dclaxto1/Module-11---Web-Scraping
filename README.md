# Module-11---Web-Scraping
Web scraping using splinter, pandas, and beautiful soup  <br />
**Part 1: Scrape Titles and Preview Text from Mars News**

Used automated browsing to visit the Mars news siteLinks to an external site. Inspected the page to identify which elements to scrape.

Extracted the titles and preview text of the news articles that you scraped. Stored the scraping results in Python data structures as follows:

Stored each title-and-preview pair in a Python dictionary and, gave each dictionary two keys: title and preview. An example is the following:

{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
Store all the dictionaries in a Python list.

Printed the list in your notebook.
![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/a23b68b1-af18-4a6b-8cc9-c9d7774b8794)

**Part 2: Scrape and Analyze Mars Weather Data**

Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site. Inspected the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Created a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, used Beautiful Soup here to continue sharpening my web scraping skills. <br />

![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/c8740159-650b-410a-8abc-9a97fa3a5aeb)

Assembled the scraped data into a Pandas DataFrame. The columns have the same headings as the table on the website. <br />

![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/7c23a840-773e-45bc-8d30-06a5a24fe2cc)

Examined the data types that are currently associated with each column. I cast (or converted) the data to the appropriate datetime, int, or float data types.<br />

![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/86d6cca7-6ef9-4c5d-8643-2704f8a0ad97)

Analyzed the dataset by using Pandas functions to answered the following questions:

1. How many months exist on Mars? **12**
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset? **705**
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? **The third month has the coldest minimum temperature on Mars, and the eighth month is the warmest**
4. Plot the results as a line graph. <br />
![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/abbf6f13-076f-444c-ba1c-56155dcc1694)

5. Which months have the lowest and the highest atmospheric pressure on Mars? **Lowest in the sixth month and highest in the ninth**
6. Find the average daily atmospheric pressure of all the months. <br />
![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/97ddc086-92e9-4583-bac2-2bcf4d2934b4)

7. Plot the results as a line graph. <br />
![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/a54b3d5f-a397-4f47-a8bb-8cfd8a7fb90e)

8. About how many terrestrial (Earth) days exist in a Martian year? **705**
9. Export the DataFrame to a CSV file. <br />
![image](https://github.com/dclaxto1/Module-11---Web-Scraping/assets/128431134/81ba7f7e-b4e0-493d-b0c9-6cf6131887ff)
