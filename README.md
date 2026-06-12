# 🏠 House Price Prediction

A machine-learning project that predicts housing prices from property features using regression, with a full pipeline from exploratory data analysis through feature engineering to model evaluation.

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)

## ✨ Overview

- Built a **Linear Regression** model to predict housing prices from multiple property features (Boston Housing dataset).
- Performed **data preprocessing, exploratory data analysis, and feature correlation analysis**.
- Used `train_test_split` for validation and visual insights via **Seaborn** and **Matplotlib**.

## 📊 Results

| Metric | Score |
| --- | --- |
| R² Score | 75.22% |
| RMSE | 4.31 |
| MAE | 3.02 |

## 🛠️ Tech Stack

Python · Pandas · NumPy · scikit-learn · Seaborn · Matplotlib · Jupyter Notebook

## 🚀 Getting Started

```bash
git clone https://github.com/fenilramani4007/House-Price-Prediciton.git
cd House-Price-Prediciton
pip install -r requirements.txt      # <!-- TODO: add a requirements.txt if missing -->
jupyter notebook                     # open the analysis notebook
```

## 📁 Project Structure

```
House-Price-Prediction/
├── notebook.ipynb     # EDA + modelling   <!-- TODO: confirm filename -->
├── data/              # dataset
├── requirements.txt
└── README.md
```

## 🔭 Possible Next Steps

- Compare against Ridge/Lasso and tree-based models (Random Forest, Gradient Boosting).
- Add cross-validation and hyperparameter tuning.
- Deploy as a small Streamlit app for interactive predictions.

## 📬 Contact

Fenil Ramani — [LinkedIn](https://linkedin.com/in/fenil-ramani-dev)

> Note: the repository is currently named `House-Price-Prediciton` (typo). Consider renaming it to `House-Price-Prediction` in repo Settings.
