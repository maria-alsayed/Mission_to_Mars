Mission_to_Mars
Overview
SpaceForward is an ambitious aerospace company that’s doing research about resource extraction from nearby planets. In this project we will be gathering information about the climate of Mars by performing full web-scraping and data analysis.

Aim
The aim of this project is to apply full web-scraping for the mission to Mars by collecting data, organizing and storing data, analyzing data, and then visually communicating our insights.

Resources
Data Source:
Mars News
Mars Temperature Data
Software: Python 3.7.13, Jupyter Notebook.
Analysis of Data and Results

1. Scrape Titles and Preview Text from Mars News

Using Splinter an automated browsing was used to visit the Mars news site. Then, we have extracted the HTML code with Beautiful Soup. After that, we have scraped and extracted the titles and preview text of the news articles and we have stored them in a dictionary.

Finally, we have exported the data to JSON file and we have saved them as mars.csv


To see the full code written in this part check mars_data_challenge_part_1.ipynb

2. Scrape and Analyze Mars Weather Data
Using Splinter an automated browsing was used to visit the Mars temperature data site. Then, we have extracted the HTML code with Beautiful Soup and we have scraped and extracted the Mars temperature table into a Pandas DataFrame and we have cleaned the table data by editing its data types.

After extracting Mars temperature table, we used this table to analyze and visualize the data by finding answers to the following questions:

How many months exist on Mars?
Which month, on average, has the lowest temperature? The highest?
Which month, on average, has the lowest atmospheric pressure? The highest?
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.

