# 2025-NASA-Space-Apps-Challenge---A-World-Away-Hunting-for-Exoplanets-with-AI
With advances in artificial intelligence and machine learning (AI/ML), it is possible to automatically analyze large sets of data collected by these missions to identify exoplanets.

# 🪐 Exoplanet AI Dashboard (v5.12)

An interactive machine learning dashboard built in Python + Tkinter to classify or cluster exoplanet candidates from NASA datasets (Kepler/TESS).  
It allows training, prediction, and visualization of results using pie, bar, and scatter plots.

---

## 🚀 Features
- Load Kepler/TESS or other exoplanet datasets (CSV or Excel)
- Automatic preprocessing, scaling, and imputation
- Detects target column for supervised training or applies clustering if none
- Saves prediction results automatically as CSV
- Graphical dashboard with:
  - Pie chart of predicted classes  
  - Bar chart of distribution  
  - Scatter plot of numeric relationships
- 100% compatible with Spyder and Tkinter GUI

---

## 🧠 Requirements
Python 3.10+  
Libraries:
```bash
pip install -r requirements.txt
