# Lazada_WebScraping_Selenium
---
## Project Objective
I was planning on scraping real time data for performing sentiment analysis based on the product comments. Product descriptions are also a good based data for constructing
recommendation system (content filtering).

## Data scaping process
1. Set up Selenium driver for scraping data.
2. Choose website platform that provide data for the project objective (Lazada).
3. Used selenium driver to automatically open web browser and get to the website page.
4. Create input engine for user to input the data collecting topic, such as technology, fashione, etc. 
5. Iterate throght the first 10 product pages and get all the products url available.
6. Based on the collected product url, interate through each one and extract neccessary data including product name, price, discount, and description.
7. Create a data frame for containing all collected data and save it to local system.
