# 🏡 House Price Prediction Project

Welcome to the **House Price Prediction Project**. This project explores supervised learning models, including polynomial regression with hyperparameter tuning, to estimate housing prices. It's designed to demonstrate your practical knowledge in machine learning to recruiters and collaborators.

---

## 📊 Project Overview

This project aims to:

* Predict house prices based on various features.
* Compare error metrics across polynomial degrees (1 to 3).
* Utilize grid search with cross-validation to fine-tune model performance.
* Evaluate using RMSE, MAE, and R² scores.

---

## ⚖️ Features

* **Polynomial Feature Expansion**
* **Standardization with `StandardScaler`**
* **GridSearchCV** for hyperparameter optimization
* Evaluation metrics:

  * RMSE (Root Mean Square Error)
  * MAE (Mean Absolute Error)
  * R² (Coefficient of Determination)

---

## 🔧 Tech Stack

| Tool                     | Purpose                              |
| ------------------------ | ------------------------------------ |
| `Python`                 | Programming Language                 |
| `pandas`                 | Data preprocessing                   |
| `numpy`                  | Numerical computation                |
| `scikit-learn`           | ML models, preprocessing, evaluation |
| `matplotlib` / `seaborn` | Data visualization                   |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Script

```bash
python house_prediction_model.ipynb
```

---

## 📚 What You'll Learn

* Data preprocessing for ML
* Feature engineering with polynomial transformations
* Hyperparameter tuning using GridSearchCV
* Model evaluation and interpretation of key metrics

---

## 📈 Sample Output

```text
Best parameters: {'alpha':1,'l1_ration':.99}
Degree 1
RMSE (Train): 34000.92
RMSE (Test): 36549.77
MAE (Test): 27890.23
R2 Score (Test): 0.82

Degree 2
RMSE (Train): 24000.54
RMSE (Test): 41023.12
MAE (Test): 31500.89
R2 Score (Test): 0.79
...
```

---

## 🚧 Future Improvements

* Export predictions to CSV
* Visualize prediction vs actual results
* Test other models (e.g., Random Forest, XGBoost)
* Add interactive Streamlit UI

---

## 👤 For Recruiters

This repository highlights:

* Clean and scalable Python code
* Familiarity with real-world ML workflows
* Ability to evaluate and compare multiple model configurations

---

## ✉️ Contributing

Pull requests are welcome! Feel free to fork the repository and improve the project.

---

## DISCLAIMER!!!!
Due to Lack of processing power there were limitations. 
1) I couldnt run for polynomial degree of 3 and above

---

## Results!!

After evaluation increasing model complexity(adding polynomial feautures) did not add any significant improvement to the model.

---


> *Built with clean code, reproducibility, and learning in mind.*
