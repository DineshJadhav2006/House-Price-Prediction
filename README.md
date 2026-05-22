# 🏠 House Price Prediction

A Machine Learning project to predict California house prices using regression models.

## 📊 Dataset
- **Source**: California Housing Dataset
- **Rows**: 20,640 | **Columns**: 10
- **Target**: `median_house_value`

## 🛠️ Tech Stack
- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Ridge, Lasso, RandomForest, HistGradientBoosting)

## 🔄 Workflow
1. Data Loading & EDA
2. Missing Value Handling (`SimpleImputer`)
3. Preprocessing Pipeline (Scaling + OneHotEncoding)
4. Model Training & Cross-Validation
5. Hyperparameter Tuning (`GridSearchCV`)
6. Evaluation (MAE, RMSE, R² Score)

## ⚙️ How to Run
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook house_price_prediction.ipynb
```

## 👤 Author
**Dinesh Jadhav**
