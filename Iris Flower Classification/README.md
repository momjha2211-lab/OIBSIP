# Task 1 — Iris Flower Classification

**Track:** Data Science
**Internship:** Oasis Infobyte Summer Internship Program (OIBSIP)
**Author:** Vivek Raj Jha

## Objective
Train a machine learning classification model to identify the species of an iris flower (Setosa, Versicolor, or Virginica) from its physical measurements.

## Tech Stack
- Python
- scikit-learn
- pandas
- matplotlib / seaborn
- Jupyter Notebook

## Dataset
The Iris dataset is loaded directly from `sklearn.datasets.load_iris()` — no external download required. It contains 150 samples across 3 species, with 4 features each: sepal length, sepal width, petal length, and petal width.

## What This Notebook Covers
- Exploratory Data Analysis (EDA): shape, data types, null value check, descriptive statistics
- Visualisations: pairplot and box plots showing feature distributions by species
- Feature selection discussion: identifying which features are most discriminative
- Train/test split (80/20)
- Training and comparing 3 classifiers: Logistic Regression, K-Nearest Neighbours, and Decision Tree
- Model evaluation: accuracy score, confusion matrix, classification report (precision, recall, F1-score)
- Identification and justification of the best-performing model

## How to Run
1. Install dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
2. Open the notebook:
   ```
   jupyter notebook Iris_Flower_Classification.ipynb
   ```
3. Run all cells from top to bottom.

## Files in This Folder
- `Iris_Flower_Classification.ipynb` — full notebook with code, outputs, and explanations
- `pairplot.png` — pairplot visualisation of features by species
- `boxplots.png` — box plots of each feature by species
- `confusion_matrices.png` — confusion matrices for all three trained models
- `README.md` — this file

## Results Summary
All three models (Logistic Regression, KNN, Decision Tree) achieve high accuracy on the test set, since the Iris dataset is largely linearly separable — especially using petal length and petal width, which proved to be the most discriminative features. See the notebook for exact accuracy figures, confusion matrices, and the final best-model selection.
