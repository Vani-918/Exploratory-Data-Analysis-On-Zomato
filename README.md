# Flavors of Insight: Zomato Restaurant Analytics

## Project Overview

This project focuses on collecting and analyzing restaurant data from Zomato using web scraping and Python. The goal is to uncover meaningful insights related to customer ratings, pricing, cuisine preferences, delivery time, and location-based trends through Exploratory Data Analysis (EDA).

The project demonstrates the complete data analytics pipeline — from data collection and cleaning to visualization and insight generation.

## Dataset Information

Source: Zomato (Web Scraping)

Records: 2000+ restaurants

Columns: 6

## Columns Description:

Restaurant – Name of the restaurant

Location – Area where the restaurant is located

Cuisine – Type of cuisine offered

Price_for_Two – Average cost for two people

Rating – Customer rating (1–5 scale)

Delivery_Time – Estimated delivery time

## Data Cleaning & Preprocessing

Identified missing values using df.isnull().sum()

Handled missing values using location-wise mode imputation

## Filled missing values for:

Rating

Cuisine

Price_for_Two

Delivery_Time

Removed rows with missing restaurant names

Verified dataset with zero null values before analysis

## Exploratory Data Analysis (EDA)

Analyzed distribution of ratings and prices

Studied cuisine popularity across locations

Compared delivery time patterns by area

Identified high-rated and affordable restaurants

Explored relationships between price, rating, and delivery efficiency

## Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

BeautifulSoup / Selenium

Jupyter Notebook

## Key Insights

Mid-range restaurants often receive higher ratings

Delivery time varies significantly by location

Certain cuisines dominate specific areas

High ratings are not always linked to high prices

Strong regional patterns exist in pricing and cuisine preferences

## Recommendations

Users can choose budget-friendly, high-rated restaurants

Restaurants can optimize pricing and delivery efficiency

Platforms can enhance location-based recommendations

## Conclusion

This project highlights how web scraping combined with data analysis can transform raw online data into actionable insights. The findings can help customers, restaurant owners, and food delivery platforms make informed decisions.
