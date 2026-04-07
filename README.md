# 📊 Course Feedback Sentiment Analysis

This project focuses on analyzing student course feedback using **Natural Language Processing (NLP)** and **Business Intelligence tools** to generate meaningful insights on learner satisfaction and teaching effectiveness.

---

## 🚀 Project Overview

This system automates the process of analyzing student feedback by classifying textual responses into **positive** and **negative sentiments**.

The project integrates **data collection, machine learning, and visualization** to help educational institutions make data-driven decisions.

---

## 🧠 Key Features

* Automated collection of feedback using Google Forms
* Real-time data storage using Google Sheets
* Data cleaning and transformation using Power Query
* Sentiment analysis using **DistilBERT (Transformer model)**
* Interactive dashboards built in Power BI
* Identification of:

  * Top-performing instructors
  * Weak-performing instructors
  * Latest feedback trends

---

## 🏗️ System Architecture

The system follows a layered architecture:

1. **Data Collection Layer**

   * Google Forms used to collect student feedback

2. **Data Storage Layer**

   * Google Sheets stores responses in real-time

3. **Processing & ML Layer**

   * Power Query for cleaning and transformation
   * Python with DistilBERT for sentiment analysis

4. **Visualization Layer**

   * Power BI dashboards for insights and reporting

---

## 🛠️ Tools & Technologies

* **Power BI** – Dashboard & visualization
* **Python** – Sentiment analysis
* **Transformers (Hugging Face)** – DistilBERT model
* **Pandas** – Data processing
* **Google Forms & Sheets** – Data collection & storage
* **DAX** – Metrics and calculations

---

## ⚙️ Sentiment Analysis Model

The project uses:

* **Model:** `distilbert-base-uncased-finetuned-sst-2-english`
* Classifies feedback into:

  * Positive
  * Negative
* Generates confidence scores for each prediction

---

## 📊 Dashboard Features

* 📌 Sentiment distribution (Pie chart)
* 📌 Feedback count by instructor (Bar chart)
* 📌 Detailed feedback table with sentiment
* 📌 KPI cards (Top & Weak instructors)
* 📌 Filters (Course, Instructor, Sentiment, Semester)
* 📌 Latest feedback highlighting

---

## 📂 Project Structure

```
course-sentiment-analysis/
│
├── data/                # Feedback dataset
├── scripts/             # Python sentiment analysis code
├── powerbi/             # Power BI dashboard files / screenshots
├── docs/                # Project report
└── README.md
```

---

## 📈 Results & Insights

* Majority of feedback is **positive**, indicating good learner satisfaction
* Negative feedback highlights areas for improvement
* System enables quick identification of:

  * Teaching quality issues
  * Course improvement opportunities

---

## 🎯 Conclusion

This project demonstrates how **AI + Data Analytics** can transform raw student feedback into actionable insights. It reduces manual effort and supports academic decision-making.

---

## 🔮 Future Improvements

* Multi-class sentiment analysis (Positive, Neutral, Negative)
* Topic extraction from feedback
* Real-time dashboard updates
* Integration with LMS systems
* Trend analysis across semesters

---

## 🔗 Author

**Ayishathul Shifana**
Bachelor of Science in Computer Science
Lincoln University College, Malaysia

---

## 📌 Note

This project is developed for academic purposes and demonstrates the practical application of NLP and data visualization in education analytics.
