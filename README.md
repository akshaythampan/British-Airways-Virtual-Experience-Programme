# British-Airways-Virtual-Experience-Programme

# Web Scraping and Customer Behavior Analysis Project


## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Data Source](#data-source)
- [Web Scraping](#web-scraping)
- [Customer Behavior Analysis](#customer-behavior-analysis)
- [Classification Model](#classification-model)
- [Insights and Analysis](#insights-and-analysis)
- [Getting Started](#getting-started)


## Introduction

Welcome to the Web Scraping and Customer Behavior Analysis Project! This repository contains the code and resources for extracting unstructured data from [Airline Quality](https://www.airlinequality.com/airline-reviews/british-airways), performing sentiment analysis on customer reviews to categorize them as positive or negative, and building a classification model to predict customer buying behavior.

## Objective

The main objective of this project is to demonstrate how web scraping can be applied to extract valuable unstructured data from the website of British Airways, analyze customer reviews using sentiment analysis to determine positive and negative sentiments, and create a classification model to predict customer buying behavior based on their reviews.

## Technologies Used

The project utilizes the following technologies:

- Python
- Jupyter Notebook
- Libraries: Beautiful Soup, Requests, NLTK, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

## Project Structure

The project repository is structured as follows:

```
|- notebooks
|   |- webscraping.ipynb
|   |- customer_behavior.ipynb
|- data
|   |- raw_data.csv
|   |- cleaned_data.csv
|- presentation
|   |- insights_analysis.pptx
|- models
|   |- classification_model.pkl
|- README.md
|- LICENSE
```

## Data Source

The data for this project is obtained from [Airline Quality](https://www.airlinequality.com/airline-reviews/british-airways). We scrape customer reviews for British Airways from the website and use it for our analysis.

## Web Scraping

The `webscraping.ipynb` notebook contains the Python code to perform web scraping. We use the Beautiful Soup and Requests libraries to extract relevant information from the website and save it as a CSV file in the `data` folder.

## Customer Behavior Analysis

In the `customer_behavior.ipynb` notebook, we analyze the customer reviews using sentiment analysis. By categorizing the reviews into positive and negative sentiments, we gain insights into customer opinions about British Airways' services.

## Classification Model

The project also involves creating a classification model to predict customer buying behavior based on their reviews. The `classification_model.pkl` file in the `models` folder contains the trained model for this purpose.

## Insights and Analysis

The key findings and analysis of the project are summarized in the `insights_analysis.pptx` presentation. It showcases the results of sentiment analysis, the performance of the classification model, and other important insights.

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies mentioned in the notebooks using `pip install -r requirements.txt`.
3. Run the `webscraping.ipynb` notebook to perform web scraping and extract the data.
4. Run the `customer_behavior.ipynb` notebook to analyze customer reviews and create the classification model.
5. Refer to the insights and analysis in the `presentation` folder for further understanding.

Feel free to explore, modify, and expand on this project as you see fit.



---

We hope you find this project helpful and insightful. If you have any questions or feedback, please don't hesitate to reach out.

Happy coding!

