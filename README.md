# Web-Scraping-JustWatch
Overview

For this project, movie and TV show data will be scraped from JustWatch, a well-known platform that collects material from a variety of streaming providers. Python is used to accomplish the scraping, with BeautifulSoup being used for HTML parsing and the queries package for HTTP queries. We take data straight out of the website's HTML structure rather than using JustWatch APIs.

Website Link:

JustWatch - https://www.justwatch.com/in/movies?release_year_from=2000

Project Workflow

Web Scraping: BeautifulSoup is a tool used by Python programs to parse HTML structure. Sending HTTP queries to the JustWatch website in order to obtain pertinent information about movies and TV shows is part of this procedure. The application gathers information by methodically browsing the HTML of the website and extracting titles, genres, release dates, and streaming platforms.

Data Filtering and Analysis: Numpy and Pandas is a potent Python data manipulation package that is used to process and filter data once it has been scraped. In this step, the data is cleaned to get rid of duplicates and inconsistencies, and it is then organized into a structured manner. Pandas facilitates comprehensive data exploration, enabling statistical analysis and the production of content insights, including the identification of patterns and trends.

Results and Insights: The filtered data analysis offers insightful information on the movies and TV series available on various streaming services. These observations could include determining the most well-liked genres, the streaming services with the biggest selections, and other pertinent details. We can learn more about the state of streaming content now by looking at these developments.

Data Visualization: Visual representations of the data, such as word clouds, bar charts are created to highlight key insights such as most watched streaming site, top ratings, top genres. This step uses libraries like WordCloud Matplotlib or Seaborn to generate clear and compelling visuals, making it easier to interpret trends and patterns in the data.

Data Export: Once the analysis is complete, the final results are saved in a CSV file. This format ensures the data is structured and easy to share, allowing for further analysis or visualization. The CSV file can be used by other tools and platforms to create charts, graphs, and reports, making the insights accessible and actionable for a wider audience.

Technologies Used

Python

Requests library for HTTP requests

BeautifulSoup for HTML parsing

Numpy for framework

Pandas for data manipulation and analysis

WordCloud for word visualuzation
