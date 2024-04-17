# Airbnb-Listings-Analysis

## Overview
The Airbnb Data Science Project aims to gather insights and develop predictive models for Airbnb listings using web scraping techniques and machine learning algorithms. By extracting data from Airbnb's website, we collect information about listing characteristics, such as prices, amenities, and ratings. This data is then cleaned, explored, and used to train a machine learning model that can predict listing prices based on various features.

## Motivation
The motivation behind this project is to provide valuable insights and tools for both hosts and guests in the Airbnb community. For hosts, understanding the factors influencing listing prices can help optimize their offerings and attract more guests. For guests, having accurate price predictions can assist in planning trips and finding accommodations that meet their budget and preferences.

## Methodology

1. **Web Scraping**: We utilize web scraping techniques to extract data from Airbnb listings. This involves scraping information from both search pages, which provide summary information about multiple listings, and detail pages, which offer more detailed information about individual listings. We web scraped data to extract information from over 76,000 listings leveraging BeautifulSoup in Python.

2. **Data Cleaning and Preprocessing**: The scraped data is cleaned and preprocessed to handle missing values, remove redundant information, and engineer new features. This step ensures that the data is suitable for analysis and modeling.

3. **Exploratory Data Analysis (EDA)**: We conduct exploratory data analysis to gain insights into the distribution of listing features, identify correlations between variables, and uncover any patterns or trends in the data.

4. **Machine Learning Model Development**: We train a machine learning model to predict listing prices based on the collected features. This involves selecting an appropriate regression algorithm, splitting the data into training and testing sets, and evaluating the model's performance using relevant metrics. We assessed listings to anticipate several factors affecting price by implementing Random Forest, SVM, and XGBoost.

5. **Results Interpretation**: The results of the machine learning model are interpreted to understand which features have the most significant impact on listing prices. Insights gained from the analysis can inform pricing strategies for hosts and help guests make informed decisions about accommodations. We applied tokenization to get listings' top ten amenities and used ggplot2, maps, ggthemes in R to visualize the data and convey results.
