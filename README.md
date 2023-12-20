# Web-Scraping-Challenge

Mars Data Scraping and Analysis
Introduction
This project involves scraping data from the Mars news site and analyzing Mars weather data. The task is divided into two parts:

Part 1: Scrape Titles and Preview Text from Mars News
Automated browsing using Splinter was employed to visit the Mars news site, and the HTML code was extracted using Beautiful Soup. The titles and preview text of the news articles were then scraped and extracted. The scraped information was stored in a Python data structure, specifically a list of dictionaries.

Part 2: Scrape and Analyze Mars Weather Data
In this part, the HTML table containing Mars weather data was extracted into a Pandas DataFrame. The columns in the DataFrame have the correct headings and data types. The data was then analyzed to answer specific questions and create data visualizations.

Data Analysis Questions:
How many months exist on Mars?
Answer: 12 months
How many Martian days' worth of data are there?
Answer: 1867
Data Visualization Questions:
Which month, on average, has the lowest temperature? The highest?
Answer: Lowest - Month 3
Warmest - Month 8
Which month, on average, has the lowest atmospheric pressure? The highest?
Answer: Lowest - Month 6
Highest - Month 9
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
Answer: ~675 days
The DataFrame resulting from the analysis was exported into a CSV file.

Tools Used
Splinter: Used for automated browsing.
Beautiful Soup: Used for HTML code extraction.
Pandas: Used for data manipulation and analysis.
Instructions for Running the Code
Ensure you have the required libraries installed:


View the results in the generated CSV file.

Conclusion
This project demonstrates the use of automated browsing and web scraping techniques to gather information from the Mars news site. Additionally, it showcases data analysis and visualization using Pandas for Mars weather data. The resulting insights are presented in a clear and organized manner for easy interpretation.

Feel free to reach out for any further clarification or details regarding the project.
