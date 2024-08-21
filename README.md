# challenge11

## Overview

This project involved completing a web scraping and data analysis challenge focused on Mars news and weather data. The goal was to practice and strengthen skills in collecting, organizing, storing, analyzing, and visualizing data. The project was divided into two main parts:

1.  **Scraping Mars News**
2.  **Scraping and Analyzing Mars Weather Data**

## Part 1: Scraping Mars News

In this section, the objective was to extract titles and preview texts from Mars news articles. The process involved the following steps:

1.  **Opened the Jupyter Notebook**: The notebook named `part_1_mars_news.ipynb` was used to guide the scraping process.
2.  **Visited the Mars News Website**: Automated browsing was used to navigate to the Mars news site.
3.  **Inspected HTML Elements**: Identified the elements to be scraped, focusing on titles and preview texts.
4.  **Used Beautiful Soup**: Created a Beautiful Soup object to extract text elements.
5.  **Stored Data**: Titles and preview texts were stored in Python dictionaries, which were then aggregated into a list.
6.  **Printed and Exported Data**: The list was printed in the notebook, and optionally, the data was exported to a JSON file.

## Part 2: Scraping and Analyzing Mars Weather Data

The second part focused on scraping and analyzing Mars weather data from an HTML table. The steps included:

1.  **Opened the Jupyter Notebook**: The notebook named `part_2_mars_weather.ipynb` was utilized for the data analysis task.
2.  **Visited the Mars Temperature Data Site**: Automated browsing was used to navigate to the data site, located at `https://static.bc-edx.com/data/web/mars_facts/temperature.html`.
3.  **Inspected HTML Table**: Identified the elements within the table to scrape data.
4.  **Used Beautiful Soup**: Data was scraped from the HTML table using Beautiful Soup, and assembled into a Pandas DataFrame.
5.  **Data Cleaning and Transformation**: Data types were adjusted to ensure appropriate formats.
6.  **Data Analysis**: Analyzed the dataset to answer questions about Martian months, days, temperature extremes, and atmospheric pressure. Results were visualized using bar charts.
7.  **Estimated Martian Year Length**: Estimated the length of a Martian year by plotting the daily minimum temperature observations.
8.  **Exported Data**: The DataFrame was exported to a CSV file.

## Files Included

-   `part_1_mars_news.ipynb` - Jupyter Notebook for scraping Mars news.
-   `part_2_mars_weather.ipynb` - Jupyter Notebook for scraping and analyzing Mars weather data.

## Instructions

1.  **Run Notebooks**: Open and run the provided Jupyter Notebooks to execute the scraping and analysis tasks.
2.  **Inspect Pages**: Use automated browsing to navigate and inspect the pages for relevant data elements.
3.  **Process Data**: Follow the steps to clean, analyze, and visualize the data as outlined in the notebooks.

## Notes

-   Ensure that the necessary Python libraries are installed before running the notebooks.
-   Data export to JSON and CSV files is optional but recommended for data sharing and further analysis.

This project served as an opportunity to enhance web scraping and data analysis skills through practical application.
