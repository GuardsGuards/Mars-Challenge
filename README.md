Module 11 Challenge: Mars Data Scraping and Analysis
Overview
In this challenge, you will be working on a comprehensive web scraping and data analysis project focusing on Mars. You will scrape data from multiple sources and use Python to store, analyze, and visualize it. This challenge is divided into two parts:

Scraping titles and preview texts from Mars news articles.
Scraping and analyzing Mars weather data from a temperature dataset.
Deliverables
Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyze Mars weather data.
Instructions
Part 1: Scrape Titles and Preview Text from Mars News
Open the Jupyter Notebook: Use the part_1_mars_news.ipynb file to complete this task.
Visit the Mars News Site: Use Splinter to automate browsing to the Mars news website.
Extract HTML Elements: Use Beautiful Soup to parse the HTML and extract titles and preview texts from news articles.
Store Data: Create a list of dictionaries where each dictionary contains the title and preview of each article.
Output: Print the list and optionally export the data to a JSON file for easy sharing.
Part 2: Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook: Use the part_2_mars_weather.ipynb file.
Visit the Mars Temperature Site: Scrape the weather data from the provided URL using Beautiful Soup.
Assemble Data: Store the scraped data in a Pandas DataFrame with appropriate column headings and data types.
Data Analysis:
Calculate how many months exist on Mars.
Determine the number of Martian days in the dataset.
Find the coldest and warmest months on Mars.
Determine which months have the lowest and highest atmospheric pressure.
Estimate the number of terrestrial days in a Martian year.
Visualization: Create bar charts to visualize the temperature and pressure data.
Export Data: Save the DataFrame as a CSV file.
