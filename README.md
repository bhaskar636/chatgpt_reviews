# chatgpt_reviews
ChatGPT Review Analysis project using NLP to analyze user sentiment, ratings, and trends over time. Performed data cleaning, sentiment classification with TextBlob, time-series analysis, and keyword extraction to identify common praises and issues. Tools used: Python, Pandas, Matplotlib, Seaborn, NLTK.

# 📊 ChatGPT Review Analysis

 Project Overview

This project focuses on analyzing user reviews of ChatGPT to understand how people feel about the product, what they appreciate, and what issues they commonly face. By applying sentiment analysis and text processing techniques, the goal is to convert raw review data into meaningful insights.

The analysis helps answer important questions such as:

* Are users generally satisfied with ChatGPT?
* What are the most common complaints?
* How has user sentiment changed over time?

---

 Dataset Information

The dataset contains the following fields:

* **Review ID** – Unique identifier for each review
* **Review** – Text feedback provided by users
* **Rating** – User satisfaction score (0–5 scale)
* **Review Date** – Date when the review was posted

---

## 🛠️ Technologies Used

* Python
* Pandas (data handling)
* NumPy
* Matplotlib & Seaborn (visualization)
* TextBlob (sentiment analysis)
* NLTK (text preprocessing)

---

 🔎 Project Workflow

 1️⃣ Data Preparation

* Loaded dataset using pandas
* Handled missing values
* Converted rating to numeric format
* Converted review date to datetime format

 2️⃣ Exploratory Data Analysis (EDA)

* Visualized rating distribution
* Analyzed how users rated ChatGPT
* Observed overall satisfaction trends

 3️⃣ Sentiment Analysis

* Calculated sentiment polarity using TextBlob
* Categorized reviews as Positive, Neutral, or Negative
* Compared sentiment with star ratings

4️⃣ Time-Series Analysis

* Extracted month and year from review dates
* Analyzed average ratings over time
* Observed changes in sentiment trends

 5️⃣ Text Processing & Keyword Extraction

* Cleaned review text (lowercase, removed punctuation & stopwords)
* Applied lemmatization
* Extracted frequently mentioned keywords
* Identified common words in negative reviews to detect major issues

---

 📈 Key Insights

* Most users show a generally positive sentiment.
* Ratings align closely with calculated sentiment polarity.
* Positive reviews frequently mention helpfulness and ease of use.
* Negative reviews often focus on accuracy issues and limitations.
* Sentiment trends reveal how user satisfaction changes over time.


🎯 Conclusion

This project demonstrates how Natural Language Processing (NLP) techniques can transform unstructured text data into actionable insights. By combining sentiment analysis, visualization, and keyword extraction, we can better understand user experiences and identify areas for product improvement.

