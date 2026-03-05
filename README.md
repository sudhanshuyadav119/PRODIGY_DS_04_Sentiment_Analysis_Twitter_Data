# PRODIGY_DS_04_Sentiment_Analysis_Twitter_Data
# Task-04: Sentiment Analysis on Twitter Data

## Internship

This project is completed as part of the **Prodigy Infotech Data Science Internship**.

## Objective

The objective of this task is to perform **sentiment analysis on social media data** to understand public opinion and identify sentiment patterns in tweets.

## Dataset

The dataset used in this project is **`twitter_training.csv`**, which contains tweets related to different topics along with their sentiment labels.

The dataset includes information such as:

* Tweet ID
* Topic or entity mentioned in the tweet
* Sentiment label
* Tweet text

These tweets are used to analyze whether the sentiment expressed is **positive, negative, or neutral**.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK (Natural Language Toolkit)

## Steps Performed

### 1. Data Loading

The dataset (`twitter_training.csv`) was loaded into a Pandas DataFrame for analysis.

### 2. Data Exploration

Basic data exploration was performed to understand the structure of the dataset and check for missing values.

### 3. Text Preprocessing

Tweets were cleaned using Natural Language Processing techniques:

* Converting text to lowercase
* Removing URLs and special characters
* Removing stopwords

### 4. Sentiment Analysis

Sentiment analysis was performed using **VADER (Valence Aware Dictionary for Sentiment Reasoning)** from the NLTK library to calculate sentiment scores.

### 5. Sentiment Classification

Tweets were classified into three sentiment categories:

* Positive
* Negative
* Neutral

### 6. Data Visualization

Visualizations were created to analyze sentiment distribution and understand sentiment patterns across different topics.

## Outcome

This project demonstrates how **Natural Language Processing (NLP)** techniques can be used to analyze large amounts of social media text data and extract meaningful insights about public sentiment.

## Project Files

* `Task04.ipynb` – Jupyter Notebook containing sentiment analysis implementation
* `twitter_training.csv` – Dataset used for sentiment analysis

## Author

**Sudhanshu Yadav**
<br>
Master’s Student in **Survey Research and Data Analytics**
