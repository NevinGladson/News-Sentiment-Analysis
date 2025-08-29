# News Sentiment Analysis: Exploring Public Opinion Through Articles

This project analyzes a dataset of news articles to understand sentiment patterns and build a predictive sentiment classifier. It demonstrates skills in **data wrangling, exploratory analysis, text preprocessing, visualization, and supervised machine learning**.

---

## 🎯 Goal
- Clean and preprocess raw text data (titles and content from news publications).
- Explore **sentiment distribution** across time and publications.
- Build a **sentiment classification model** to predict positive/negative tone.
- Provide insights into how different news outlets publish content with varying sentiment.

---

## 📊 Dataset
- Source: Publicly available dataset of news articles.  
- Key fields: `title`, `content`, `publication`, `date`, `sentiment`, `sentiment_confidence`.  
- Size: ~tens of thousands of rows (train/test split used).  
- Target variable: **Sentiment** (Positive vs Negative).

---

## 🔎 Approach
1. **Data Cleaning**
   - Removed nulls, duplicates, unwanted symbols, digits, underscores.
   - Standardized text using **lemmatization** and stopword removal.

2. **Exploratory Data Analysis (EDA)**
   - Sentiment distribution (positive vs negative).
   - Trends by **date** and **publication**.
   - Visualizations of class imbalance and sentiment confidence.

3. **Text Preprocessing**
   - Tokenization and lemmatization.
   - Vectorization using **CountVectorizer**.

4. **Modeling**
   - Train/test split based on publication distribution.
   - Baseline model: Sentiment prediction using Bag-of-Words features.
   - Evaluation on test set.

---

## ✅ Key Findings
- Sentiment varies significantly across publications.
- Positive sentiment dominates but negative sentiment shows spikes at specific time periods.
- The classifier achieves solid accuracy and provides a foundation for more advanced NLP methods (TF-IDF, word embeddings, deep learning).

---

## ⚙️ Tech Stack
- **Python**: pandas, numpy, scikit-learn, matplotlib, seaborn, nltk, TextBlob
- **Jupyter Notebook** for interactive analysis
