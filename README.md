# 🏡 California House Price Prediction using XGBoost

This project predicts housing prices in California based on various demographic and geographic features. The model is trained using the **California Housing Dataset** from `scikit-learn`, with **XGBoost Regressor** as the core algorithm for accurate prediction.

---

## 📊 Dataset

- **Source**: California Housing dataset from `sklearn.datasets`
- **Features**: Median income, house age, average rooms, population, latitude, longitude, etc.
- **Target**: Median house value (in $100,000s)

---

## 🧰 Technologies Used

- Python
- Pandas & NumPy
- Matplotlib
- scikit-learn
- XGBoost

---

## 🚀 Project Workflow

1. **Import Dependencies**
2. **Load and Explore the Dataset**
3. **Data Preprocessing**
   - Feature scaling using `StandardScaler`
4. **Train-Test Split**
5. **Model Training**
   - Using `XGBRegressor`
6. **Model Evaluation**
   - Metrics: R² Score, MAE

---

## ✅ Results

- **R² Score (Training Set)**: ~0.94
- **Mean Absolute Error (Training Set)**: ~0.19
- **R² Score (Test Set)**: ~0.83
- **Mean Absolute Error (Test Set)**: ~0.31
- **Model Used**: XGBoost Regressor (default parameters)

---

## ▶️ How to Run

1. Clone the repository or download the notebook.
2. Make sure required libraries are installed (`xgboost`, `pandas`, `scikit-learn`, etc.).
3. Run the notebook step-by-step in Jupyter or Colab.

---

## 💡 Possible Improvements

- Trying other models (e.g., Random Forest, LightGBM)

---

## 🙏 Acknowledgments

- California Housing dataset from [scikit-learn](https://scikit-learn.org/)
- XGBoost open-source contributors
