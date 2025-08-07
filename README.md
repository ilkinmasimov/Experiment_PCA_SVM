# Machine Learning Experiment Report

## Classification of Wine Dataset Using PCA and SVM Algorithms


---

## Overview

This project focuses on applying Principal Component Analysis (PCA) and Support Vector Machines (SVM) to classify wines using the Wine dataset. The experiment includes both manual and Scikit-learn implementations of PCA to demonstrate its impact on dimensionality reduction and model performance.

---

## Contents

1. Load the Wine Dataset  
2. PCA for Dimensionality Reduction  
3. Model Generation with SVM  
4. PCA Implementation in Scikit-learn  
5. Result Analysis  
6. Conclusion  

---

## 1. Load the Wine Dataset

- Loaded using Pandas from the UCI Machine Learning Repository.
- Assigned meaningful column names.
- Dataset split: 70% training and 30% testing.

---

## 2. PCA for Dimensionality Reduction

- Standardized features using `StandardScaler`.
- Computed the covariance matrix and performed eigenvalue decomposition.
- Selected the top two principal components based on explained variance.
- Projected data into 2D for visualization and further modeling.

---

## 3. Model Generation with SVM

- SVM classifier created with a linear kernel using `SVC` from Scikit-learn.
- Two versions were tested:
  - **Without PCA** (full feature set)
  - **With PCA** (top 2 components)
- Compared both models in terms of accuracy and computation time.

---

## 4. PCA Implementation in Scikit-learn

- Validated manual PCA with `sklearn.decomposition.PCA`.
- Visualized explained variance using Plotly.
- Compared variance retention between components.

---

## 5. Result Analysis

- Accuracy comparison:
  - Without PCA: *[insert value]*  
  - With PCA (2 components): *[insert value]*
- PCA reduced training time while maintaining acceptable accuracy.
- Two components retained a significant portion of the variance.

---

## 6. Conclusion

- Successfully classified wine data using SVM with and without PCA.
- PCA proved effective in reducing dimensionality without major performance loss.
- Demonstrated the efficiency and practicality of PCA in machine learning workflows.

---

## Notes

- Visualizations and screenshots of code/results are included in the full report.
- Accuracy values need to be filled in based on actual model output.
