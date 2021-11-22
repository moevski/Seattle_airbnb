# Seattle AirBnB Data Analysis Project
Udacity Data Scientist Nanodegree Project 1: "Write a Data Science Blog Post"

## Introduction
Seattle Airbnb Open Dataset that include Airbnb activities in Seattle, WA, USA during 2016</br>

 
## Motivation
Try to answer the following questions based on available data to find out factors affecting pricing strategy.

1. How does average units price change around the year and across days of the week?
2. Suppose a new host want to predict an average price for his unit, can we estimate this based on available data?
3. What are the top factors that affect unit prices
4. Does reviews (pos or neg) correlate with unit availability?
5. Is there a pattern in positive reviews, can we visualize the most common words mentioned in these positive reviews?</br>

## Findings Summary
First, average unit listing prices changes during the year, there is a high season between week 27 to week 40 where prices are over the weekly average. I also found that prices are usually higher than average in weekends compared to work days.

Second, I built linear regression model to predict the price based on selected features, and analyized most influential features that affect the price that include property type and location (neighbourhood_group)

Third, I used sentiment analysis model to analyize comments but I failed to find a coorelation between positive comments and unit availability, finally I developed wordcloud model to display the most frequently used works in positive comments and displayed these words

The main findings of the code can be found at the post available [here](https://moevski.medium.com/top-factors-affecting-pricing-strategy-on-airbnb-in-seattle-4196ad16b50f)</br>

## Files Description
**listings.csv:** original dataset including full descriptions and average review score 

**reviews.csv:** original dataset including unique id for each reviewer and detailed comments

**calendar.csv:** original dataset including listing id and the price and availability per day
**exploratory_analysis.ipynb:** The main Jupyter notebook file that include detailed step by step analysis and findings

**requirements.txt:** used packages for analysis

**README.md:** This file</br>

## Requirements
I used Jupyter notebook version 5.7.0 with python 3.6.3 kernel. to install required libraries to run the code in exploratory_analysis.ipynb, please execute:</br> 
'pip install -r requirements.txt'</br>


## Acknowledgements
1. Dataset used are part of Airbnb inside, downloaded from kaggle https://www.kaggle.com/airbnb/seattle (License - CC0: Public Domain)</br>

