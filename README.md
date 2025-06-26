# Breast Cancer Detection using Logistic Regression

This project aims to build a Logistic Regression model to detect breast cancer using the **Breast Cancer Wisconsin (Diagnostic) Data Set**. It applies **logistic regression** after analyzing, cleaning, and normalizing the data to predict whether a tumor is benign(B) or malignant(M).

---

## Dataset

- **Source:** [UCI Machine Learning](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
- Each sample is labeled as **benign (B)** or **malignant (M)**.

---

## Project Workflow

### 1. **Analyzing the Dataset**
- Inspect shape, types, and summary statistics of the data
- Visualize class distribution and feature correlations

### 2. **Cleaning the Data**
- Drop unnecessary columns (e.g., ID)
- Handle missing values (if any)

### 3. **Normalizing the Data**
- Use`StandardScaler` to apply feature scaling for better model performance

### 4. **Training and Testing the Model**
- Train the model using Logistic Regression.
- Evaluate performance using confusion matrices and accuracy scores for both training and test sets

---

## Results

- **High accuracy** on both training and testing datasets (~98%)
- **No signs of overfitting or underfitting** — model generalizes well

---

## Requirements

libraries used:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib` / `seaborn`

---

## Conclusion

This project show us how logistic regression can effectively classify tumors as benign or malignant with minimal preprocessing and handling. The pipeline from data analysis to model evaluation is simple, interpretable, and accurate.
Kindly Note this project was done for educational purposes ONLY and is not intended for any medicial use.
