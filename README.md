# DecodeLabs AI/ML Internship — Batch 2026


> A collection of hands-on AI/ML projects completed during the **DecodeLabs Virtual Internship (Batch 2026)**. 
> Each project follows an **IPO Model** (Input → Process → Output) with clean, well-commented notebooks.

---

## ‍ Intern Details

| Field | Details |
|---|---|
| **Name** | Ramroshith Alluri |
| **Enrollment** | 25CS003660 |
| **College** | Sir Padampat Singhania University (SPSU), Rajasthan |
| **Branch** | B.Tech CSE (AI/ML) |
| **Internship** | DecodeLabs — Virtual AI/ML Internship, Batch 2026 |

---

## Project Structure

```
decode-labs-internship/
│
├── chatbot.ipynb # Project 1 — Rule-Based AI Chatbot
├── p2_classification.ipynb # Project 2 — Iris Flower Classification (KNN)
└── tech_stack_recommender.ipynb # Project 3 — Tech Stack Recommender (TF-IDF)
```

---

## Projects

---

### Project 1 — Rule-Based AI Chatbot (`chatbot.ipynb`)

A deterministic chatbot built using Python dictionary lookups — no ML, no hallucinations. Pure logic.

**Key Concepts:**
- Rule-based NLP with O(1) dictionary lookup
- Input sanitization (lowercase + strip)
- Graceful fallback for unknown queries
- IPO Model: raw text → sanitize → dictionary match → response

**Supported Topics:** AI concepts, DecodeLabs info, jokes, greetings, help commands

**Tech Stack:** `Python` (core only — no external libraries)

**Sample Interaction:**
```
You: what is machine learning
Bot: ML is a subset of AI where systems learn from data to improve over time.

You: joke
Bot: Why do programmers prefer dark mode? Because light attracts bugs! 
```

---

### Project 2 — Iris Flower Classification (`p2_classification.ipynb`)

End-to-end ML pipeline on the classic Iris dataset using K-Nearest Neighbors.

**Key Concepts:**
- Feature scaling with `StandardScaler`
- Train/test split (80/20) with shuffle
- KNN classification (K=5)
- Elbow Method to find optimal K
- Confusion matrix heatmap visualization
- F1 Score vs Accuracy — understanding the "Accuracy Mirage"

**Dataset:** Iris — 150 samples, 4 features, 3 classes (Setosa, Versicolor, Virginica)

**Results:**

| Metric | Score |
|---|---|
| Accuracy | ~96.67% |
| F1 Score (weighted) | ~0.9667 |
| Optimal K (Elbow) | 5 |

**Tech Stack:** `pandas` · `numpy` · `scikit-learn` · `matplotlib` · `seaborn`

---

### Project 3 — Tech Stack Recommender (`tech_stack_recommender.ipynb`)

A content-based job role recommender system using TF-IDF vectorization and cosine similarity. Enter your skills → get your top matching job roles.

**Key Concepts:**
- TF-IDF vectorization on a 20-role job skills corpus
- Cosine similarity for skill-to-role matching
- 4-step pipeline: Ingestion → Scoring → Sorting → Filtering
- Cold Start Problem detection and fallback strategy
- Full similarity bar chart visualization

**Dataset:** 20 job roles with curated skill sets (Data Scientist, ML Engineer, DevOps, Frontend, etc.)

**Sample Output:**
```
Input Skills: ["python", "machine learning", "deep learning", "tensorflow", "data analysis"]

#1 → Machine Learning Engineer (Match: 87.3%)
#2 → AI Research Scientist (Match: 76.1%)
#3 → Data Scientist (Match: 71.4%)
```

**Tech Stack:** `pandas` · `numpy` · `scikit-learn` (TF-IDF, cosine similarity) · `matplotlib`

---

## ️ Setup & Installation

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/ramroshithalluri-commits/decode-labs-internship.git
cd decode-labs-internship

# 2. Install dependencies
pip install numpy pandas scikit-learn matplotlib seaborn jupyter

# 3. Launch Jupyter
jupyter notebook
```

Then open any `.ipynb` file and run all cells.

---

## Dependencies

```
numpy
pandas
scikit-learn
matplotlib
seaborn
jupyter
```

---

## Skills Demonstrated

| Skill | Projects |
|---|---|
| Python Programming | All |
| Data Preprocessing & EDA | P2, P3 |
| Machine Learning (KNN) | P2 |
| NLP / TF-IDF Vectorization | P3 |
| Cosine Similarity | P3 |
| Data Visualization | P2, P3 |
| Rule-Based AI Systems | P1 |
| Recommendation Systems | P3 |

---

## About DecodeLabs

[DecodeLabs](https://www.decodelabs.tech) is a virtual internship platform that helps students and young professionals build career-ready AI/ML skills through practical, mentor-guided projects with structured weekly checkpoints.

---

## License

This repository is for educational purposes as part of the DecodeLabs Internship Program, Batch 2026.

---

<p align="center">Built with by Ramroshith Alluri | DecodeLabs Batch 2026 </p>
