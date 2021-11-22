# Seattle AirBnB Data Analysis Project
Udacity Data Scientist Nanodegree Project 1: "Write a Data Science Blog Post"

### Table of Contents

1. Introduction (#Introduction)
2. Motivation (#Motivation)
3. Findings Summary (#Findings_Summary)
4. Files Description (#Files_Description)
5. Requirements (#Requirements)
6. Acknowledgements (#Acknowledgements)

## Introduction <a name="Introduction"></a>
Seattle Airbnb Open Dataset that include Airbnb activities in Seattle, WA, USA during 2016</br>

 
## Motivation <a name="Motivation"></a>
Try to answer the following questions based on available data to find out factors affecting pricing strategy.

1. How does average units price change around the year and across days of the week?
2. Suppose a new host want to predict an average price for his unit, can we estimate this based on available data?
3. What are the top factors that affect unit prices
4. Does reviews (pos or neg) correlate with unit availability?
5. Is there a pattern in positive reviews, can we visualize the most common words mentioned in these positive reviews?</br>

## Findings Summary <a name="Findings_Summary"></a>
First, average unit listing prices changes during the year, there is a high season between week 27 to week 40 where prices are over the weekly average. I also found that prices are usually higher than average in weekends compared to work days.

Second, I built linear regression model to predict the price based on selected features, and analyized most influential features that affect the price that include property type and location (neighbourhood_group)

Third, I used sentiment analysis model to analyize comments but I failed to find a coorelation between positive comments and unit availability, finally I developed wordcloud model to display the most frequently used works in positive comments and displayed these words

The main findings of the code can be found at the post available [here](https://medium.com/@ericvenarusso2/what-are-the-most-common-programming-languages-used-in-brazil-8d630b76df2f)</br>

## Files Description <a name="Files_Description"></a>
**listings.csv:** original dataset including full descriptions and average review score 

**reviews.csv:** original dataset including unique id for each reviewer and detailed comments

**calendar.csv:** original dataset including listing id and the price and availability per day
**exploratory_analysis.ipynb:** The main Jupyter notebook file that include detailed step by step analysis and findings

**requirements.txt:** used packages for analysis

**README.md:** This file</br>

## Requirements <a name="Requirements"></a>
I used Jupyter notebook version 5.7.0 with python 3.6.3 kernel. to install required libraries to run the code in exploratory_analysis.ipynb, please execute:</br> 
'pip install -r requirements.txt'</br>


## Acknowledgements <a name="Acknowledgements"></a>
1. Dataset used are part of Airbnb inside, downloaded from kaggle https://www.kaggle.com/airbnb/seattle (License - CC0: Public Domain)</br>

