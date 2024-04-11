# Project Description

In this project, we aim at exploring the potential influence of amazon's self-brand products on search ranking position. Using and API, we perform 20 different product searches and scrape all listings obtained, its characteristics (i.e, price, sponsored product indicator, rating, etc) as well as it reviews. 
We perform minimal preprocessing and data cleansing as well as sentiment analysis using TextBlob on user reviews and add the obtained polarity score as a regressor. 
We perform two linear regressions, using either rating or polarity score and we compare in both cases the significant coefficients of Amazon brand product and sponsored products dummy variables and draw conclusions. 

# Notebooks and Data
Find within 'scraped data' folder, a csv file for each product search containing all scraped data of listings.
Find within 'notebooks' folder, the notebook used to do scraping through API, the notebook that gives an alternative way of scraping using BeautifulSoup and the notebook where preprocessing and analysis is done.

# Results

