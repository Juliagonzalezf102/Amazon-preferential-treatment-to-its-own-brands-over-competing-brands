# Project Description

In this project, we aim at exploring the potential influence of amazon's self-brand products on search ranking position. Using and API, we perform 20 different product searches and scrape all listings obtained, its characteristics (i.e, price, sponsored product indicator, rating, etc) as well as it reviews. 
We perform minimal preprocessing and data cleansing as well as sentiment analysis using TextBlob on user reviews and add the obtained polarity score as a regressor. 
We perform two linear regressions, using either rating or polarity score and we compare in both cases the significant coefficients of Amazon brand product and sponsored products dummy variables and draw conclusions. 

# Notebooks and Data
Find within 'scraped data' folder, a csv file for each product search containing all scraped data of listings.
Find within 'notebooks' folder, the notebook used to do scraping through API, the notebook that gives an alternative way of scraping using BeautifulSoup and the notebook where preprocessing and analysis is done.

# Results
The effect of positioning of Amazon brand products is found to be as large as 62% - 72% of that of sponsored products within the two first pages of search results. Moreover, the effect of self-preferencing is found to be larger when using polarity scores obtained from sentiment analysis of reviews instead of average rating, potentially revealing that the cost to the consumer of such practices is even larger when considering a more nuanced view of the product's value to the consumer.
