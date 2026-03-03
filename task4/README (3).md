# Task-04: Sentiment Analysis on Social Media Data

## 📌 Objective
The objective of this task is to **analyze and visualize sentiment patterns in social media data** to understand **public opinion and attitudes towards specific topics or brands**.

---

## 📊 Dataset
- **Dataset Name:** Twitter Sentiment Dataset  
- **File:** `twitter_training.csv`
- **Source:** Prodigy InfoTech – Sample Dataset
- **Key Columns:**
  - `topic` – Entity or brand being discussed  
  - `tweet` – Social media text data  
  - `sentiment` – Original sentiment label  

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:
- Renamed columns for consistency
- Converted text to lowercase
- Removed URLs, special characters, and punctuation
- Removed stopwords
- Created a cleaned text column for analysis

---

## 🧠 Sentiment Analysis
- Used **VADER (Valence Aware Dictionary and sEntiment Reasoner)** for sentiment scoring
- Classified tweets into:
  - **Positive**
  - **Negative**
  - **Neutral**
- Generated a new column: `predicted_sentiment`

---

## 📈 Visualizations
The following visualizations were created:
- Sentiment distribution bar chart
- Sentiment percentage pie chart
- Sentiment distribution by **top entities (brands/topics)**
- Word cloud for positive sentiment tweets

---

## 🔍 Key Insights
- Positive sentiment dominates most Twitter discussions
- Some entities receive significantly higher negative sentiment
- Word clouds highlight commonly used positive expressions
- Sentiment analysis helps understand public opinion and brand perception

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- WordCloud


---

## 📁 Project Structure
└── twitter_training.csv
└── task_04.ipynb
└── README.md
└── overall_sentimental_distribution.png
└── sentimental_patterns_for_top_5_brands.png
└── top_keywords.png


---

## ✅ Conclusion
This task demonstrates how sentiment analysis and visualization techniques can be used to analyze social media data and gain meaningful insights into public opinion and brand perception.

---

## 👨‍💻 Author
**Om Dhaigude**  
Prodigy InfoTech – Data Science Internship

