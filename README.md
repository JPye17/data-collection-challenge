# data-collection-challenge
KU Module 11 data-collection-challenge

Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

## This project consists of two deliverables:
* Deliverable 1: Scraping titles and preview text from the Mars news site.
* Deliverable 2: Scraping, analyzing, and visualizing Mars weather data.
  
## Deliverable 1: Scraping Mars News
In the first part of the project, we use Splinter and BeautifulSoup to scrape the Mars news website and collect the titles and preview text of recent news articles.

Steps:
* Visit the Website: The Mars News site is accessed using Splinter.
* Scrape the Website: We create a BeautifulSoup object to extract text elements from the website.
* Store the Results: The titles and previews are stored in a list of dictionaries. Each dictionary has two keys: title and preview.

## Deliverable 2: Mars Weather Data Analysis
In the second part of the project, we scrape and analyze Mars weather data from the Mars Temperature Data Site.

Steps:
* Visit the Website: The website is accessed using Splinter.
* Scrape the Data: A BeautifulSoup object is used to extract table data containing Mars weather information.
* Store the Data: The extracted data is stored in a Pandas DataFrame with appropriate column headers.
* Prepare Data for Analysis: Data types are adjusted to facilitate analysis (e.g., converting dates to datetime format).
* Analyze the Data: Key questions are answered using Pandas functions:
* How many months exist on Mars?
* How many Martian days (sols) worth of data exist?
* What are the coldest and warmest months on Mars based on average minimum temperature?
* Which months have the lowest and highest atmospheric pressure?
* How long is a Martian year in Earth days?
## Visualizations:
* Average Minimum Temperature by Month: A bar chart showing the coldest and warmest months on Mars.
* Average Atmospheric Pressure by Month: A bar chart showing the lowest and highest atmospheric pressures on Mars.
