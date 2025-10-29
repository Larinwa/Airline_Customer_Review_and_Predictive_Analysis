# Airline Customer Review and Predictive Analysis
A comprehensive data science project that explores customer experience, satisfaction, and booking behavior in the airline industry through web scraping, sentiment analysis, topic modeling, and predictive modeling.

---

## Overview

The project was conducted during a data science internship to extract meaningful insights from real-world airline reviews and booking data.  
It combines Natural Language Processing (NLP) with Machine Learning (ML) to understand customer sentiments and forecast booking tendencies.

---

## Key Components

### 1. Web Scraping
Collected **1,000 verified airline customer reviews** from a public review platform using:
- `BeautifulSoup`
- `Requests`
- `Pandas`

The extracted reviews were stored in a structured `.csv` file for further analysis.

### 2. Sentiment Analysis
Applied **VADER (Valence Aware Dictionary and sEntiment Reasoner)** from NLTK to classify customer opinions as:
- Positive  
- Negative  
- Neutral  

**Findings:**  
54.6% Positive | 44.7% Negative | 0.7% Neutral

### 3. Text Preprocessing & Topic Modeling
Cleaned and tokenized reviews through:
- Lowercasing  
- Stopword removal  
- Tokenization and lemmatization  
- Special character filtering  

Applied **Latent Dirichlet Allocation (LDA)** using `gensim` to reveal dominant discussion topics such as:
- Customer service  
- Flight cancellations  
- Food quality  
- Seat comfort  
- Business class experience  

A **word cloud** visualization highlighted frequently mentioned terms like *service*, *flight*, *seat*, and *food*.

### 4. Predictive Modeling (Booking Behavior)
Built supervised learning models to predict whether a user would complete a booking based on attributes like:
- Sales channel  
- Trip type  
- Purchase lead time  
- Booking origin  

Models implemented:
- **Random Forest Classifier**
- **XGBoost Classifier**

Performance evaluation included:
- Confusion matrix  
- Accuracy and F1-score  
- Feature importance visualization

---

## Insights
- Customer **service quality** emerged as a critical factor driving both satisfaction and complaints.  
- **Flight cancellations** and **amenity shortages** were key sources of negative sentiment.  
- Predictive analysis revealed that **purchase timing** and **trip purpose** strongly influence booking completion.  

---

## Tools & Libraries
`Python`, `BeautifulSoup`, `Requests`, `NLTK`, `Gensim`, `WordCloud`, `Matplotlib`, `Seaborn`, `Pandas`, `NumPy`, `Scikit-learn`, `XGBoost`

---

## Outcome
The analysis provided data-backed recommendations for improving customer experience and helped demonstrate how integrated NLP and ML workflows can guide **business decisions in the aviation sector**.

---

Feel free to explore the repository and notebooks for implementation details.
