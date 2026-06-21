# 🎮 Machine Learning & AI Algorithms Project

## 📌 Overview
This project explores machine learning and search algorithms across three main sections:
- Regression analysis using player review data
- Classification of game success using Steam review features
- Comparison of classical search algorithms vs reinforcement learning

All datasets are based on real Steam game data scraped and cleaned for analysis.

---

## 📊 Dataset Information

- **Regression Dataset:** `video_games_clean_sample (1).csv`  
  Used to predict Metacritic scores based on player reviews.

- **Classification Dataset:** `cleaned_dataset (2).csv`  
  Used to classify game success using player review features.

---

## 🤖 Section 1: Regression (Game Score Prediction)

📁 Notebook: `End_to_End_MLR_+_POLYREG_(1)_(1) (3).ipynb`

### Goal
Predict **Metacritic scores** using player-review-based features.

### Models Used
- Multiple Linear Regression (MLR)
- Polynomial Regression

### Key Idea
Instead of critic reviews, this model relies only on **user-generated reviews** to estimate professional review scores.

---

## 🎯 Section 2: Classification (Game Success Prediction)

📁 Notebook: `FULL_CLASSIFICATION_(1)_(2).ipynb`

### Goal
Predict whether a game is **successful or not** based on player review data.

### Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)

### Key Idea
Uses Steam player feedback signals to classify game performance without critic influence.

---

## 🧠 Section 3: AI Search Algorithms Comparison

📁 Notebook: `Section1_(1).ipynb`

### Algorithms Implemented
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- A* Search
- Q-Learning (Reinforcement Learning)

### Goal
Compare classical search strategies with reinforcement learning in problem-solving efficiency and behavior.

---

## 📄 Report

- `combined_report (2).pdf`  
  Contains full explanation, methodology, results, and analysis across all three sections.

---

## 🛠️ Tools & Libraries
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🚀 Project Goals
- Analyze whether **player reviews alone** can predict game success
- Compare regression vs classification performance on gaming data
- Study differences between classical AI search and reinforcement learning

---

## 📌 How to Run
1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
