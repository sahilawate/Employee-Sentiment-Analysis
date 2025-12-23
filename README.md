Employee Sentiment Analysis

Project Overview

This project analyzes internal employee email communication to assess sentiment, engagement levels, and potential flight risk. Using Natural Language Processing (NLP) and machine learning techniques, the project transforms unlabeled email data into meaningful insights that can support HR decision-making and employee retention strategies.

The dataset provided was unlabeled, requiring sentiment classification to be derived programmatically before further analysis.

Objectives

Automatically label employee emails as Positive, Neutral, or Negative

Perform exploratory data analysis to identify communication trends

Compute monthly sentiment scores for each employee

Rank employees based on sentiment performance

Identify potential flight-risk employees using a rolling 30-day window

Build a linear regression model to analyze sentiment trends

Key Results

Monthly sentiment scores were successfully computed for all employees

Top three positive and negative employees were identified for each month

Employees exhibiting four or more negative emails within a rolling 30-day window were flagged as flight risks

A linear regression model showed that message frequency and verbosity influence sentiment trends

Project Structure

Employee-Sentiment-Analysis/
├── notebook/
│   └── employee_sentiment_analysis.ipynb
├── visualizations/
│   ├── sentiment_distribution.png
│   ├── message_trends.png
│   └── employee_activity.png
├── report/
│   └── Employee_Sentiment_Analysis_Report.docx
├── README.md
└── requirements.txt

Technologies Used

Python
Pandas, NumPy
NLTK (VADER Sentiment Analyzer)
Scikit-learn
Matplotlib, Seaborn