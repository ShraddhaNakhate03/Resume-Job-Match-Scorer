# 📄 Resume Job Match Scorer

## 📌 Project Overview

The **Resume Job Match Scorer** is a Streamlit-based web application that analyzes how well a resume matches a given job description. It uses **Natural Language Processing (NLP)** techniques such as **TF-IDF vectorization** and **Cosine Similarity** to calculate a match score between the uploaded resume and the job requirements.

This tool helps job seekers **optimize their resumes by identifying how closely their skills and experience align with job descriptions**.

---

## 🚀 Features

* Upload **Resume in PDF format**
* Paste **Job Description**
* Calculate **Resume–Job Match Score**
* Visual **match score indicator**
* Suggestions based on **similarity score**
* Built with **NLP techniques**

---

## 🧠 How It Works

1. User uploads a **resume PDF**
2. User pastes the **job description**
3. Text is **cleaned and preprocessed**
4. Stopwords are removed using **NLTK**
5. Text is converted into vectors using **TF-IDF**
6. **Cosine Similarity** calculates the match percentage
7. Results are displayed with a **visual score indicator**

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Framework

* Streamlit

### Libraries Used

* Scikit-learn
* NLTK
* PyPDF2
* Matplotlib
* Regular Expressions (re)

### NLP Techniques

* Text preprocessing
* Stopword removal
* TF-IDF Vectorization
* Cosine Similarity

---

## 📂 Project Structure

```
Resume-Job-Match-Scorer/
│
├── app.py          # Main Streamlit application
├── README.md       # Project documentation
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/ShraddhaNakhate03/resume-job-match-scorer.git
```

Navigate to the project folder:

```bash
cd resume-job-match-scorer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 📊 Output

The application provides:

* **Match Score (%)**
* Visual **similarity indicator**
* Resume alignment feedback:

| Score    | Feedback        |
| -------- | --------------- |
| 0 – 40   | Low Match       |
| 40 – 70  | Good Match      |
| 70 – 100 | Excellent Match |

---

## 🎯 Use Cases

* Resume optimization for job applications
* Career guidance tools
* HR resume screening
* Personal job preparation

---

## ⭐ Key Skills Demonstrated

* Natural Language Processing (NLP)
* Text Similarity Analysis
* Python Application Development
* Streamlit Web Apps
* Data Preprocessing
* Machine Learning Concepts

---

## 🚀 Future Improvements

* Keyword extraction from job descriptions
* Resume improvement suggestions
* Support for **multiple resume formats**
* Deploy application using **Streamlit Cloud**
* Add **skill gap analysis**

---

## 📌 Conclusion

This project demonstrates how **Natural Language Processing and Machine Learning techniques can be applied to automate resume screening and job matching**. It showcases practical implementation of **TF-IDF vectorization and cosine similarity in a real-world application**.
