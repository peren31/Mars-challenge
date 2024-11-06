# Mars Data Scrape and Analysis 

**Mars Data Scraping and Analysis**
<p>The challenge centers on obtaining and analyzing data from Mars, covering recent news articles and Martian weather data. Using web scraping techniques, the project extracts, structures, and visualizes information to gain insights into Mars’s environment and research developments.

**Project Overview**
This project is divided into two main parts:

Mars News Scraping: Collects titles and preview text of Mars news articles.
Mars Weather Analysis: Scrapes and analyzes Mars weather data, focusing on temperature, atmospheric pressure, and seasonal patterns.
Deliverables
Deliverable 1: A dataset of Mars news articles with titles and previews.
Deliverable 2: A structured analysis of Mars weather data, saved as a CSV file.
Setup and Installation
Clone or Download the Repository: Ensure you have the required files in your working directory.

Install Required Libraries: You’ll need the following Python libraries:

pandas
requests
BeautifulSoup
matplotlib
splinter (for automated browsing)
Jupyter Notebook: Open the provided .ipynb files in Jupyter Notebook to follow the analysis steps.

**Instructions**
Part 1: Mars News Scraping
Goal: Scrape recent news articles from the Mars News website.
Steps:
Open part_1_mars_news.ipynb.
Use automated browsing to navigate to the Mars news page.
Extract the title and preview text of each article.
Save the results as a list of dictionaries, where each dictionary has:
title: The article’s title.
preview: A brief summary of the article.
Output: A JSON or dictionary-based dataset of Mars news articles.
Part 2: Mars Weather Data Analysis
Goal: Scrape and analyze weather data from the Mars Temperature Data site.

Steps:

Open part_2_mars_weather.ipynb.
Scrape the data table, which includes Martian dates, temperatures, and atmospheric pressures.
Load the data into a Pandas DataFrame and clean it as needed.
Analysis:

Calculate and visualize average temperature and pressure by Martian month.
Estimate the length of a Martian year in Earth days by analyzing the temperature cycles.
Output: A comprehensive analysis of Martian weather trends, saved as a CSV file.

**Analysis Questions**
How many months are in a Martian year?
What are the coldest and warmest months on Mars at the location of the Curiosity rover?
Which months experience the highest and lowest atmospheric pressures?
How long is a Martian year in terms of Earth days?
Results
The final results include a collection of Mars news articles, an analysis of Martian weather patterns, and visualizations that reveal trends in Martian climate.

**Additional Notes**
This project is a great way to practice web scraping, data analysis, and visualization in Python.
For sharing the data, you can optionally export the news articles as JSON and the weather data as CSV.
