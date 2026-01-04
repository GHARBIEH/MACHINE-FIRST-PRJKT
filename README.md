
---

## 👥 Team Members
- **Zaid Gharbieh**
- **Anas Alhabashi**

> 🔹 **Work distribution:** 50% Zaid / 50% Anas  
> Both team members contributed equally to the project design, implementation, and analysis.

---

## 📂 Project Structure
The repository currently contains the following notebooks:

- **Data Ingestion**
  - Loading raw datasets
  - Memory optimization
  - Merging tables into a unified dataset

- **Preprocessing**
  - Data cleaning
  - Handling missing values
  - Feature preparation

- **Exploratory Data Analysis (EDA)**
  - Descriptive statistics
  - Data distributions
  - Initial insights and patterns

- **Task A: Classification** — Predicting whether a product will be reordered.
- ### Models Implemented
- Logistic Regression (L2 regularization, class-weighted)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (Linear & RBF kernels)
- Decision Tree
- Random Forest
- Gradient Boosting (XGBoost / LightGBM)

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Precision–Recall AUC (Average Precision)
- Confusion Matrix (raw and normalized)
- Probability Calibration Curves

### Notes
- Computationally expensive models (KNN, SVM, Random Forest) were evaluated on validation subsamples.
- Models showed stable performance. 
- 
- **Task B: Regression** — Predicting the average number of days between customer orders.
- ### Target Variable
- **Mean days between orders** (average time between consecutive customer purchases).

### Models Implemented
- Ordinary Least Squares (OLS)
- Ridge, Lasso, Elastic Net
- K-Nearest Neighbors Regressor
- Support Vector Regressor (Linear & RBF)
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor (XGBoost / LightGBM)

### Evaluation Metrics
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² and Adjusted R²

### Diagnostics
- Residual analysis was partially implemented.
- Full heteroscedasticity tests and Q-Q plots were planned but not fully completed due to time limits.

---

## 🧪 Dataset
The project uses the **Instacart Online Grocery Shopping Dataset**, processed locally from the `DATA/` directory.
and you must download the 'data' file and put it inside the noteboks folder in order to work correctly from the google drive link:
https://drive.google.com/drive/folders/1BxKUxfs_hzOfOnhQUZCzA_pCeFiNiHsd?usp=drive_link
