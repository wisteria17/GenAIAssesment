# AI Resume Screening System with Tracing

## 📌 Project Overview
This project is an AI-based Resume Screening System that evaluates resumes against a job description using Natural Language Processing (NLP) techniques.

It calculates a match score and provides a decision (Selected/Rejected) along with an explanation (tracing) of matched and missing skills.

---

## 🚀 Features
- Resume vs Job Description matching
- TF-IDF Vectorization
- Cosine Similarity Score
- Match Percentage Output
- Selection Decision
- Explainable AI (Tracing):
  - Matched Skills
  - Missing Skills

---

## 🧠 Tech Stack
- Python
- Scikit-learn
- NLP (TF-IDF)
- Jupyter Notebook / Google Colab

---

## ⚙️ How It Works
1. Input resume and job description
2. Preprocess text (cleaning & formatting)
3. Convert text into numerical vectors using TF-IDF
4. Calculate similarity using cosine similarity
5. Extract relevant skills from both texts
6. Compare skills to identify:
   - Matched skills
   - Missing skills
7. Generate final output with score and decision

---

## 📊 Example Output

Match Score: 35.35%  
Decision: Rejected  

Matched Skills:
- python  
- machine learning  
- data analysis  

Missing Skills:
- sql  
- deep learning  

---

## 📂 Project Structure
