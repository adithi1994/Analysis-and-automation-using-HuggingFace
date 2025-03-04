
# Analyzing and Automating Insights with Hugging Face

## 📌 Project Overview

This project aims to leverage **data analysis techniques and AI-driven automation** to extract meaningful insights from a **large dataset of product reviews**. Using **machine learning models and Hugging Face's pre-trained NLP models**, the system performs **sentiment analysis and text summarization** to help businesses understand customer feedback at scale.

## 🚀 Features
- **Sentiment Analysis:** Classifies reviews as **positive, neutral, or negative** using both **Logistic Regression (TF-IDF)** and **Hugging Face transformer models**.
- **AI-powered Summarization:** Automates the extraction of key insights from unstructured review data.
- **Data Cleaning & Preprocessing:** Handles missing values, converts timestamps, and creates new features like **helpfulness ratio**.
- **Exploratory Data Analysis (EDA):** Visualizes sentiment trends to understand customer feedback better.
- **Comparison of Models:** Evaluates **traditional ML models** against **Hugging Face NLP models** in terms of efficiency and accuracy.

## 📊 Dataset
- **Source:** [Kaggle (Reviews.csv)](https://www.kaggle.com/)
- **Size:** 568,454 reviews, 10 columns
- **Key Columns:**
  - `ProductId`, `UserId`, `ProfileName`, `HelpfulnessNumerator`, `HelpfulnessDenominator`
  - `Score`, `Time`, `Summary`, `Text`
  
## 🛠️ Tech Stack
- **Programming Language:** Python
- **Machine Learning:** Logistic Regression with TF-IDF
- **Deep Learning Models:** Hugging Face Transformer (`pipeline("sentiment-analysis")`)
- **Libraries Used:**
  - `pandas`, `numpy` - Data manipulation
  - `matplotlib`, `seaborn` - Data visualization
  - `sklearn` - Machine learning models
  - `transformers` - Pre-trained NLP models
  - `nltk` - Text processing

## 📌 Approach

1. **Data Preprocessing**
   - Handled missing values (e.g., filling summaries with review text).
   - Converted timestamps into human-readable format.
   - Created a `HelpfulnessRatio` feature for better review credibility.

2. **Sentiment Analysis**
   - **TF-IDF + Logistic Regression** for baseline sentiment classification.
   - **Hugging Face Pre-trained Model** for advanced sentiment analysis.

3. **Comparing Models**
   - **Logistic Regression (TF-IDF)**: Good for simple tasks but needs feature engineering.
   - **Hugging Face Transformer**: Pre-trained, context-aware, and more accurate.

## 🔥 Results & Insights
- The **Hugging Face model** significantly outperforms **traditional ML models**, especially for nuanced sentiment detection.
- **Automating customer feedback analysis** can **enhance business decision-making**.
- **AI-powered summarization** saves time and extracts key takeaways efficiently.

