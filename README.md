# **Email Spam Classification using NLP**

## **📄 Overview**

This project demonstrates a Natural Language Processing (NLP) approach to classify emails as spam or ham (non-spam). The goal is to explore and understand patterns in email messages using Exploratory Data Analysis (EDA) and prepare the data for future classification tasks.

---

## **🛠️ Features**

- **Data cleaning and preprocessing**: Ensures the data is suitable for analysis.
- **Visual insights into message structure**: Analyzes character, word, and sentence counts in emails.
- **Exploratory Data Analysis (EDA)**: Utilizes histograms, pie charts, and pair plots for deeper insights.
- **Feature engineering**: Creates features helpful for spam classification.

---

## **📂 Dataset**

The dataset contains two columns:
1. **Message**: The email text.
2. **Category**: Labels indicating whether the email is spam or ham.

### **Label Encoding**
- `0` → Ham
- `1` → Spam

---

## **📋 Prerequisites**

Ensure the following Python libraries are installed:

- `pandas`
- `numpy`
- `nltk`
- `matplotlib`
- `seaborn`
- `wordcloud`
- `sklearn`

---

## **📊 Exploratory Data Analysis (EDA)**

### **Key Insights from the Dataset**:

- **Message Structure Analysis**:
  - **Character counts**: Ham messages tend to be longer than spam messages.
  - **Word counts**: Ham messages usually contain more words.
  - **Sentence counts**: Ham messages generally have more sentences.

### **Visualizations**:

1. **Category Distribution**:
   - A pie chart showing the ratio of ham and spam emails.

2. **Histograms**:
   - Compare the distribution of character, word, and sentence counts between ham and spam emails.

3. **Pair Plot**:
   - Visualizes relationships between features (e.g., number of characters vs. words) with categorical separation.

---

## **🛠️ Implementation Steps**

### **Data Preprocessing**:

1. Remove duplicate messages.
2. Remove messages with invalid labels.
3. Encode the **Category** column to numerical values (0 for ham and 1 for spam).
4. Add new features for analysis:
   - **no_characters**: Number of characters in a message.
   - **no_words**: Number of words in a message.
   - **no_sentences**: Number of sentences in a message.

### **Analysis and Visualization**:

1. Generate descriptive statistics for both ham and spam emails.
2. Use visualizations (pie chart, histograms, pair plots) to interpret patterns and relationships between features.

---

## **🔍 Results**

- **Ham emails**: Tend to be longer, more descriptive, and contain more words and sentences.
- **Spam emails**: Often use shorter sentences, fewer words, but exhibit distinctive patterns that make them identifiable.
- The EDA results provide valuable insights and serve as a foundation for building machine learning models for spam detection.

---

## **📈 Future Work**

- **Implement machine learning models** for classification (e.g., Naive Bayes, SVM, or deep learning).
- **Optimize preprocessing steps** for better feature extraction and representation.
- **Expand the dataset** with multilingual support to improve model generalization.

---
