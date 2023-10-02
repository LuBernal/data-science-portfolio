# Tasty Bytes Recipe Recommendation Report 🍽️📊

## Introduction and Context

This project is part of my final examination to obtain the Data Scientist Professional certificate at DataCamp. The examination includes generating a data science report for a fictional recipe app and presenting it to a hypothetical marketing team. 

### Problem Statement

In 2020, during the Covid-19 pandemic, Tasty Bytes started as a recipe search engine. The Product Team features a favorite recipe on the homepage, which can boost website traffic significantly more than others. The Head of Data Science wants us to predict recipes that will be popular 80% of the time while avoiding unpopular ones. This aims to optimize recipe selection, improve user engagement, and increase subscriptions. 📈

## Data Analysis

In this report, I analyze data provided by Tasty Bytes' product manager, including recipe information and its impact on website traffic.

#### Missing Nutritional Values

During data cleaning, I observed a pattern regarding missing nutritional values and their effect on higher traffic. A statistical test showed a significant correlation. Omitting nutritional values could increase website engagement. 🧮

#### Recipe Categories

I investigated correlations between recipe categories and their proportions of high and low traffic, using stacked bar charts to visualize the results. 🍰

## Model Development

As the target feature is binary, I focused on binary classification models, evaluating precision and false positive rate (FPR).

I started with a Majority Class Classifier as a simple baseline model, providing context for more advanced models. 📊

I then explored Logistic Regression and K-Nearest Neighbors (KNN) with hyperparameter tuning for better performance. 🤖

## Conclusion and Recommendations

Our analysis suggests strategies to optimize recipe selection:

- Omit nutritional values to increase website engagement.
- Spotlight recipes from categories like Meat, One Dish Meal, Pork, Potato, and Vegetable.
- Avoid featuring recipes from categories like Beverages, Breakfast, and Chicken. 

This report guides Tasty Bytes in enhancing its service, enriching customer experiences, and thriving in the culinary industry. 🍳

## Other Project-Related Content

This folder also contains the presentation used during the examination and the given CSV file to be used in the project. 📄📂
