# Retail Churn Prediction Model

**Tools:** Python, scikit-learn, Jupyter Notebook  
**Theme:** Green & White

## Project Summary
Built a machine learning model using behavioral and transactional data to identify customers likely to churn.
- Achieved ~85% model accuracy and strong ROC-AUC on synthetic data.
- Supported targeted retention strategies that reduced churn in a simulated environment.

## Files
- `data/retail_churn_data.csv` - Realistic synthetic dataset (2000 customers)
- `notebooks/Retail_Churn_Prediction.ipynb` - Jupyter notebook with EDA, modeling, and evaluation
- `images/` - Visualization images (heatmap, ROC curve, feature importance)
- `requirements.txt` - Python dependencies

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

