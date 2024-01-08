# Mars Data Analysis Project

## Overview
This project involves web scraping and data analysis focused on Mars. It includes two main parts: extracting news articles related to Mars and analyzing weather data from the Martian surface. This project aims to gather and analyze current information about Mars, providing insights into its weather patterns and recent news developments.

## Technologies Used
- Python
- Libraries: Beautiful Soup, Pandas, Splinter, Matplotlib
- Jupyter Notebook

## Part 1: Mars News Scraping
In this section, we scrape titles and preview text from Mars news articles.

### Objectives:
1. Use automated browsing with Splinter to visit the Mars news site.
2. Extract titles and preview text of news articles using Beautiful Soup.
3. Store the information in Python data structures (list of dictionaries).

### Methodology:
- Visited the Mars news website.
- Identified HTML elements, classes, and IDs for the required data.
- Extracted and stored data in the specified format.

## Part 2: Mars Weather Data Analysis
This section focuses on scraping and analyzing weather data from Mars.

### Objectives:
1. Scrape Mars Temperature Data from the specified website.
2. Organize the data into a Pandas DataFrame.
3. Analyze the data to answer specific questions regarding Martian weather patterns.

### Analysis:
- Determined the number of Martian months and days in the dataset.
- Calculated the average minimum daily temperature and atmospheric pressure for each month.
- Created bar charts to visually represent these averages.
- Estimated the number of terrestrial days in a Martian year based on data analysis.

## Exporting Data
The final analyzed data was exported as a CSV file (available in the Output folder) for further use or distribution.

## Conclusion
This project successfully scraped and analyzed data related to Mars, providing valuable insights into its atmospheric conditions and current news. The use of Python and its libraries enabled efficient data processing and visualization.
