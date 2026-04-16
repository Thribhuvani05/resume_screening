# 🚀 AI Resume Screening System with LangChain & LangSmith

## 📌 Overview

This project is an AI-powered Resume Screening System that evaluates candidates based on a job description.

It extracts skills, matches them with requirements, assigns a score, and provides an explanation.

---

## 🧠 Features

* Skill Extraction from Resume
* Resume vs Job Description Matching
* Candidate Scoring (0–100)
* Explainable AI Output
* LangSmith Tracing for debugging

---

## ⚙️ Tech Stack

* Python
* LangChain
* OpenAI API
* LangSmith

---

## 🔄 Pipeline Flow

Resume → Extraction → Matching → Scoring → Explanation

---

## 📊 Sample Results

| Candidate | Score |
| --------- | ----- |
| Strong    | ~90   |
| Average   | ~65   |
| Weak      | ~30   |

---

## 🔍 LangSmith Tracing

* 3 runs (Strong, Average, Weak)
* Each step tracked:

  * Extract
  * Match
  * Score
  * Explain

---

## 🐞 Debugging

Handled hallucination by:

* Adding strict prompt rules
* Preventing assumptions

---

## 📎 How to Run

1. Open notebook in Google Colab
2. Add OpenAI API key
3. Run all cells

---


