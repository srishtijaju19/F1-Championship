# Formula 1 World Championship (1950–2024) Analysis

## 📌 Overview
This project explores the historical Formula 1 dataset (1950–2024) and applies exploratory data analysis (EDA) and machine learning to uncover insights and make predictions related to race results and driver/team performance.

## 📂 Project Structure



## 📊 Dataset
- **Source**: [Kaggle - Formula 1 World Championship](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
- Contains data from 1950 to 2024:
  - Races, drivers, constructors, qualifying, pit stops, lap times, standings, and more.
- Key tables:
  - `races.csv`, `drivers.csv`, `constructor_standings.csv`, `results.csv`, `qualifying.csv`

## 🧠 Approach

### 🔍 Exploratory Data Analysis
- Number of races over time, top drivers/constructors
- Dominant teams by decade
- Track popularity and country-wise stats
- Visualization of starting position vs. race finish
- Weather or track impact (if available)
- Time series forecasting for driver or constructor points

### 🤖 Machine Learning
- Predict race winner based on qualifying, constructor, and driver data
- Classification model: Logistic Regression / Random Forest / XGBoost
- Feature engineering: combine multiple datasets for modeling
- Evaluation: Accuracy, Confusion Matrix, ROC-AUC

## 📈 Results
- EDA revealed the rise and dominance of certain teams (e.g., Ferrari, Red Bull)
- ML model predicted podium finishes with ~75% accuracy
- Starting grid and constructor ranking were strong predictors

## ⚙️ Tools & Libraries
- Python, pandas, numpy
- seaborn, matplotlib, plotly
- scikit-learn, XGBoost
- Jupyter Notebook

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/f1-analysis.git
cd f1-analysis

pip install -r requirements.txt
jupyter notebook notebooks/f1_eda.ipynb
