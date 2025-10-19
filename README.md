# 🏠 Regression and Evaluation – California Housing Dataset

## 📘 Project Overview

This project demonstrates the application of various **regression models** on the **California Housing Dataset** to predict median house values.
The goal is to understand and compare the performance of multiple supervised learning algorithms through detailed evaluation metrics.

---

## 🎯 Objective

Evaluate the understanding of regression techniques in supervised learning by:

* Building multiple regression models
* Training them on real-world data
* Comparing their performance using key evaluation metrics such as R², MSE, and MAE.

---

## 🧩 Dataset

**California Housing Dataset** (from `sklearn.datasets`)
This dataset contains features describing California housing data such as:

* MedInc (Median Income)
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude
  and the target variable **MedHouseValue** (median house price).

---

## ⚙️ Steps and Workflow

1. **Data Loading**
   Used `fetch_california_housing()` from `sklearn.datasets` to load the data.

2. **Data Preprocessing**

   * Converted the dataset into a pandas DataFrame
   * Standardized numerical features using `StandardScaler`
   * Split the data into training and testing sets

3. **Model Training**
   Implemented and compared the following regression models:

   * Linear Regression
   * Decision Tree Regressor
   * Random Forest Regressor
   * Gradient Boosting Regressor
   * Support Vector Regressor (SVR)

4. **Evaluation Metrics**

   * Mean Squared Error (MSE)
   * Mean Absolute Error (MAE)
   * R² Score

5. **Visualization**

   * Performance comparison through bar plots and metrics visualization using `matplotlib` and `seaborn`.

---

## 📊 Results Summary

| Model             | R² Score | Remarks                        |
| :---------------- | :------: | :----------------------------- |
| Linear Regression |   ~0.57  | Baseline performance           |
| Decision Tree     |   ~0.62  | Improved non-linear fit        |
| Random Forest     |   ~0.80  | Best performing model          |
| Gradient Boosting |   ~0.77  | Strong performance             |
| SVR               |   ~0.73  | Good but computationally heavy |

✅ **Random Forest** achieved the highest R² score, indicating strong predictive capability.

---

## 🧠 Key Learnings

* Model complexity and ensemble techniques significantly improve regression performance.
* Evaluation metrics like R², MSE, and MAE provide complementary insights.
* Data scaling enhances model efficiency, especially for SVR.

---

## 🛠️ Technologies Used

* **Python**
* **scikit-learn**
* **pandas**, **numpy**
* **matplotlib**, **seaborn**

---

## ▶️ How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/Assignment-9.git
   cd Assignment-9
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook

   ```bash
   jupyter notebook Assignment-9.ipynb
   ```
4. Run all cells to reproduce the results.

---

## 🏁 Conclusion

Among the tested models, **Random Forest Regressor** delivered the most accurate predictions, proving that ensemble methods are powerful tools for regression tasks on real-world data.

---

**Author:** Suroora Fathima
**Date:** October 2025
**Project Type:** Machine Learning – Regression Evaluation
