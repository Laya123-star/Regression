# 🏠 California Housing Regression Analysis

A supervised machine learning project focused on applying and comparing
multiple regression algorithms on real-world housing data.

---

## 📘 Project Overview

- This project performs a detailed regression analysis using the **California Housing dataset**
  available from the `sklearn` library.
- The dataset contains **20,640 records and 8 numerical features**, along with a continuous
  target variable representing median house value.
- The objective is to understand how different housing-related features influence house prices
  and to compare the performance of multiple regression models.

**🎯 Objective:**

The project includes:

 🔹 Data loading and preprocessing  
 🔹 Feature scaling and data preparation  
 🔹 Implementation of multiple regression algorithms  
 🔹 Model evaluation and comparison  
 🔹 Visualizations and result interpretation  
 🔹 Clean and reproducible Google Collab Notebook  

---

## 📂 Dataset Description

The dataset represents housing information collected from California census data.

| Feature Name | Description |
|-------------|------------|
| MedInc | Median income in the block group |
| HouseAge | Median house age in the block group |
| AveRooms | Average number of rooms per household |
| AveBedrms | Average number of bedrooms per household |
| Population | Population of the block group |
| AveOccup | Average household occupancy |
| Latitude | Latitude of the block group |
| Longitude | Longitude of the block group |
| MedHouseValue | Median house value (target variable) |

---

## 🧹 Preprocessing Steps

The following preprocessing steps were performed to prepare the data for modeling:

✔ **Dataset Loading:**  
The California Housing dataset was loaded using `fetch_california_housing` from sklearn.

✔ **DataFrame Conversion:**  
The dataset was converted into a Pandas DataFrame for easier handling and analysis.

✔ **Missing Value Check:**  
The dataset was checked for missing values, and no missing entries were found.

✔ **Outlier Removal:**  
Outliers were detected and removed from the target variable (`MedHouseValue`) using the
Interquartile Range (IQR) method to reduce the influence of extreme house prices.

✔ **Train–Test Split:**  
The dataset was split into training and testing sets to evaluate model performance on unseen data.

✔ **Feature Scaling:**  
Standardization was applied where required (Linear Regression and SVR) to ensure features
were on a comparable scale.

---

## 📈 Regression Models Implemented

The following regression algorithms were implemented and evaluated:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor (SVR)  

Each model was trained using the same dataset and evaluated using consistent metrics.

---

## 📊 Model Evaluation Metrics

Each regression model was evaluated using:

- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **R-squared Score (R²)**  

These metrics help measure prediction accuracy and overall model performance.

---

## 📊 Visualizations Included

| Purpose | Visualization Type |
|-------|-------------------|
| Actual vs Predicted Values | Scatter Plot |
| Feature Importance | Bar Chart |
| Model Comparison | Tabular Comparison |

The visualizations help interpret model performance and understand feature influence.

---

## 🧠 Key Observations

- ✔ Ensemble models performed better than basic regression models.
- ✔ Gradient Boosting Regressor achieved the highest R² score.
- ✔ Median income and geographic features showed strong influence on house prices.
- ✔ Simpler models were easier to interpret but less accurate.

---

## 🛠 Tech Stack

| Tool | Purpose |
|----|--------|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Scikit-learn | Machine learning models |
| Google Colab | Execution environment |

---

## 📁 Repository Structure

ML-Assignment-2-Regression/

├── 📄 Regression.ipynb  
├── 📄 README.md  

---

## 🚀 How to Run the Project

1. Open the notebook in **Google Colab** or Jupyter Notebook.
2. Run all cells in sequence.
3. The notebook will perform preprocessing, model training, evaluation, and visualization automatically.

---

## 📌 Submission Note

This repository is submitted as part of an academic assignment for evaluating
regression techniques in supervised learning.
