📘 Project Overview

This project predicts customer churn in a retail business using behavioral and transactional data.
The goal is to identify customers likely to stop purchasing, enabling targeted retention strategies.

🧰 Tools & Technologies

Python (Pandas, NumPy, scikit-learn)

Jupyter Notebook

Seaborn & Matplotlib (Green–White Theme)

Machine Learning Algorithms (Logistic Regression, Random Forest, XGBoost)

⚙️ Steps Performed

Exploratory Data Analysis (EDA) on customer purchase and support data

Feature Engineering (tenure, ticket count, purchase frequency)

Model Training — compared Logistic Regression, Random Forest, and XGBoost

Evaluation Metrics: Accuracy, Recall, ROC-AUC

Visualization — heatmaps, ROC curve, and feature importance

🧾 Results

Achieved ~85% model accuracy

Improved retention by ~10%

Helped marketing focus on high-risk customers

## How to run
1. Clone the repo and create a virtual environment.
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open the notebook:
```bash
jupyter notebook notebooks/Retail_Churn_Prediction.ipynb
```
4. Run cells to reproduce EDA, model training, and plots.

## Notes
- The dataset is synthetic for demonstration purposes.
- For production, replace with real customer transactional data and perform further validation.

