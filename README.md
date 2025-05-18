# 🧠 Cognitively Distorted Language Analysis (CDS)

A research-grade NLP pipeline for detecting cognitively distorted language in social media posts, comparing prevalence across depressed and non-depressed users on BlueSky, and training BERT-based models for depression classification.

> 📘 Based on the methodology from **Rutter et al. (2025)** and expanded with modern ML tools.

---

## 📌 Project Goals

- Detect **Cognitive Distortions** using rule-based phrase matching
- Compare **CDS prevalence** between depressed and random users
- Train and evaluate a **BERT model** to detect depression
- Collect user data from **BlueSky** using age, gender, and depression filters
- Calcuated CDS prevalance ratio, Perplexity, and sentiment analysis.

---

## 📊 Results & Evaluation
Includes:

- CDS prevalence comparison
- Bootstrapped confidence intervals
- Model F1, AUC, and confusion matrices
- Perplexity score
- Sentiment Analysis

---

🙏 Acknowledgments
[Rutter et al. (2025)] - CDS paper and methodology
HuggingFace - Transformers
DeepFace - Age/Gender detection
BlueSky - Data source

---

## 🚀 Setup Instructions

### ✅ Clone the Repo

```bash
git clone https://github.com/Blank31/Cognitively-Distorted-Language-Analysis-CDS-.git
cd Cognitively-Distorted-Language-Analysis-CDS-

