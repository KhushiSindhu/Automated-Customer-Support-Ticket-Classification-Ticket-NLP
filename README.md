# Automated Customer Support Ticket Classification

This repository contains the solution for automating the customer support ticket system for a financial company through natural language processing (NLP) techniques.

## Problem Statement
Customer complaints are vital indicators of a financial company's product and service shortcomings. This project aims to automate the classification of customer complaints into relevant categories, enabling swift issue resolution and enhancing customer satisfaction.

## Business Goal
The primary objective is to build a model capable of classifying customer complaints based on the products/services they pertain to. By employing non-negative matrix factorization (NMF) for topic modeling, the project aims to identify patterns and recurring words within tickets, allowing for efficient segregation into five categories:
- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

## Dataset
The dataset comprises 78,313 customer complaints in .json format, encompassing various features. The initial step involves converting this dataset into a DataFrame for further processing.

## Expected Tasks
1. **Data Loading**: Loading the provided dataset.
2. **Text Preprocessing**: Cleaning and preparing text data for analysis.
3. **Exploratory Data Analysis (EDA)**: Understanding the dataset's characteristics.
4. **Feature Extraction**: Extracting relevant features from the text data.
5. **Topic Modelling**: Employing NMF for topic modeling to classify complaints.
6. **Model Building using Supervised Learning**: Utilizing labeled data for training.
7. **Model Training and Evaluation**: Training and evaluating models, including logistic regression, naive Bayes, decision tree, and random forest.
8. **Model Inference**: Using the trained model for classifying new customer support tickets.



## Note
Upon finalizing complaint clusters/categories, a labeled dataset was created for supervised learning model training. Evaluation metrics have been used to determine the best-performing model among logistic regression, naive Bayes, decision tree, and random forest.
