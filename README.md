
# Tennis Dataset – Gini Impurity Calculation for All Splits

## 📌 Project Overview

This project demonstrates how to calculate Gini Impurity for all possible splits in a Tennis dataset using Python.

The main objective is to evaluate different feature splits and identify the best split using Gini Reduction, which is an important concept in Decision Tree Classification.

## 📂 Dataset Description

- Dataset Name: Unique Tennis Dataset
- Total Records: 16
- Target Column: Play
- Input Features:
  - Outlook
  - Court
  - Wind
  - Temperature

## 🎯 Objectives

Calculate the following values for every possible split:

1. Parent Gini Impurity
2. Left Child Gini Impurity
3. Right Child Gini Impurity
4. Weighted Child Gini Impurity
5. Gini Reduction

## 🧮 Formulas Used

### 1. Parent Gini Impurity

Gini = 1 - Σ(pᵢ²)

### 2. Weighted Child Gini Impurity

Weighted Gini = (Left Weight × Left Gini) + (Right Weight × Right Gini)

### 3. Gini Reduction

Gini Reduction = Parent Gini - Weighted Child Gini

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- VS Code

## 📁 Project Structure

```text
Tennis-Gini-Impurity/
│
├── hasini_jakkana.ipynb
├── unique_tennis_gini_dataset.csv
├── tennis_gini_all_splits.csv
├── tennis_gini_best_split_by_feature.csv
└── README.md
```

## ⚙️ Implementation Steps

1. Import the required Python libraries.
2. Load the Tennis dataset.
3. Identify input features and the target column.
4. Define a function to calculate Gini Impurity.
5. Calculate Parent Gini Impurity.
6. Generate all unique possible binary splits.
7. Calculate Left Child Gini Impurity.
8. Calculate Right Child Gini Impurity.
9. Calculate Weighted Child Gini Impurity.
10. Calculate Gini Reduction.
11. Identify the best split.
12. Export the results into CSV files.

## 📊 Output Files

| File Name | Description |
|---|---|
| tennis_gini_all_splits.csv | Gini calculations for all splits |
| tennis_gini_best_split_by_feature.csv | Best split for each feature |

## 🏆 Expected Outcome

The project calculates all five required Gini values for every generated split and identifies the best split based on the highest Gini Reduction.

## 📝 Conclusion

Gini Impurity is an important measure used in Decision Trees to evaluate the quality of a split.

A lower Weighted Child Gini indicates purer child nodes, while a higher Gini Reduction indicates a better split.

This assignment provides practical experience in understanding how Decision Tree algorithms select the best feature for splitting data.

---

**Assignment:** Student Activity – Calculate Gini for All Splits

**Topic:** Machine Learning – Decision Tree Classification
