# **Email Spam Classification using NLP**




## **📄 Overview**

#### This project demonstrates a Natural Language Processing (NLP) approach to classify emails as spam or ham (non-spam). The goal is to understand patterns in email messages using exploratory data analysis (EDA) and prepare the data for future classification tasks.


## **🛠️ Features**

#### -> Data cleaning and preprocessing

#### -> Visual insights into message structure (characters, words, sentences)

#### -> Exploratory Data Analysis (EDA) with histograms and pair plots

#### -> Useful feature engineering for spam classification tasks

## 📂 Dataset

#### The dataset contains two columns:

####         1) Message: The email text

####         2) Category: Labels indicating whether the email is spam or ham

### Label Encoding:

#### * 0 → Ham

#### * 1 → Spam

## 📋 Prerequisites

#### Ensure the following Python libraries are installed:

#### * pandas

#### * numpy

#### * nltk

#### * matplotlib

#### * seaborn

#### * wordcloud

#### * sklearn

## 📊 Exploratory Data Analysis

### Key Insights from the Dataset:

#### ->Message Structure Analysis:

 #### 1) Character counts: Ham messages tend to be longer than spam messages.

 #### 2) Word counts: Ham messages usually contain more words.

 #### 3) Sentence counts: Ham messages generally have more sentences.

### Visualizations:

#### 1. Category Distribution

##### Pie chart showing the ratio of ham and spam emails.

#### 2. Histograms

##### Compare the distribution of character, word, and sentence counts between ham and spam.

#### 3. Pair Plot


##### Visualizes relationships between features (e.g., number of characters vs. words) with categorical separation.

## 🛠️ Implementation Steps

### Data Preprocessing

#### -> Remove duplicate messages.


#### -> Remove messages with invalid labels.

#### -> Encode the Category column to numerical values (0 and 1).

#### -> Add new features for analysis:

#### *) no_characters: Number of characters in a message.

#### *)no_words: Number of words in a message.

#### *) no_sentences: Number of sentences in a message.

### Analysis and Visualization

#### -> Generate descriptive statistics for ham and spam emails.

#### -> Use visualizations (pie chart, histograms, pair plots) to interpret patterns.

## 🔍 Results

#### -> Ham emails are generally longer and more descriptive than spam emails.

#### -> Spam emails often use shorter sentences and fewer words but exhibit identifiable patterns that make them distinguishable.

#### -> This EDA serves as a foundation for building machine learning models for spam detection.

## 📈 Future Work


#### -> Implement machine learning models for classification (e.g., Naive Bayes, SVM, or deep learning).

#### -> Optimize preprocessing steps for feature extraction.

#### -> Expand dataset with multilingual support.
