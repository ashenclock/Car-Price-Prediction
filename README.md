# 🚗 Car Price Prediction

Machine learning project for car price estimation using the Kaggle *Car Price Prediction* dataset.

## 🎯 Goal

Predict vehicle price from technical and categorical features (brand, engine specs, body type, etc.) with robust preprocessing and model selection.

## 📊 What the notebook covers

- Data loading and cleaning (`CarPrice_Assignment.csv`)
- Brand normalization and category cleanup
- Feature engineering + encoding + scaling
- Model training and comparison
- Hyperparameter tuning with `GridSearchCV`
- Dimensionality reduction analysis with PCA

## 🤖 Models

- `RandomForestRegressor`
- `KernelRidge`

## 📈 Evaluation

Primary metrics:

- **R²**
- **MSE**

The notebook includes plots and prediction-vs-ground-truth visual analysis.

## 🚀 Run locally

```bash
git clone https://github.com/ashenclock/Car-Price-Prediction.git
cd Car-Price-Prediction
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook PrML.ipynb
```

## 📁 Files

- `PrML.ipynb`: full workflow
- `CarPrice_Assignment.csv`: dataset used in the analysis

