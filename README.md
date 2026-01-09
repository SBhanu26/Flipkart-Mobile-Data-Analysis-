# Flipkart-Mobile-Data-Analysis-
Web scraping and exploratory data analysis of Flipkart mobile listings to uncover pricing patterns, brand performance, hardware impact (RAM &amp; storage), discounts, and customer ratings. The project transforms raw web data into actionable insights to identify value-for-money smartphones in India’s competitive market.

Project Overview :

This project focuses on web scraping and exploratory data analysis (EDA) of mobile phone listings from Flipkart. The goal is to understand pricing patterns, brand performance, hardware impact, and customer satisfaction in India’s smartphone market by transforming raw web data into meaningful insights.

Business Problem :

Flipkart offers a wide range of smartphones across brands, price segments, and specifications, making it difficult to identify:

• What truly drives pricing

• Whether higher prices lead to better ratings

• How hardware features influence customer satisfaction

A structured data analysis is required to support better pricing, positioning, and value-for-money decisions.

Objectives :

• Analyze overall pricing, ratings, and product distribution

• Study the impact of RAM and storage on price

• Examine the relationship between price, discounts, and ratings

• Evaluate brand-wise performance

• Identify value-for-money smartphones

Tools & Technologies :

Python

• BeautifulSoup & Requests – Web scraping

• Pandas & NumPy – Data cleaning & manipulation

• Matplotlib & Seaborn – Data visualization

• Jupyter Notebook – Analysis environment

Data Collection :

• Scraped Flipkart mobile listings using browser developer tools

• Extracted product details such as price, brand, ratings, specifications, and discounts

• Converted unstructured HTML data into structured datasets

Data Cleaning Steps :

• Handled missing values using appropriate statistical methods

• Extracted brand names from product titles

• Used regex to extract RAM, storage, and battery capacity

• Split combined review & rating columns

• Converted all features into correct data types

• Removed unnecessary columns

Key Insights :

• Budget & mid-range phones dominate (₹5,000–₹30,000)

• Strong competition among brands like Realme, Samsung, Vivo, Redmi, POCO

• No strong correlation between price and rating

• Many low-priced phones receive high ratings (≈4.4)

• Storage impacts price more than RAM

• Discounts increase with higher original prices

• Customer satisfaction depends more on value for money than premium pricing

Analysis Performed :

• Univariate Analysis

• Bivariate Analysis

• Multivariate Analysis

• Correlation analysis

• Visual insights using histograms, bar plots, box plots, scatter plots, and heatmaps

Conclusion :

The Indian smartphone market on Flipkart is highly competitive and value-driven. While prices are influenced by RAM and storage, customer ratings remain consistently high across price segments. Premium phones are fewer but well-rated, whereas budget and mid-range devices dominate both listings and engagement. Overall, pricing fairness and user experience matter more than high-end specifications.
