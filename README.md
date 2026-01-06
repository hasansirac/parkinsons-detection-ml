# Parkinson’s Disease Detection (Speech Features) — Machine Learning

Early detection of Parkinson’s disease (PD) is important for improving patient outcomes.
This project builds and compares classical ML classifiers using high-dimensional speech features.

## Overview
- Task: Binary classification (PD vs Healthy)
- Data: 755 samples, 753 numerical features (high-dimensional speech descriptors)
- Split: 80/20 stratified train-test split
- Metrics: Accuracy, Precision, Recall, F1-score (F1 emphasized due to class imbalance)

## Models
- Logistic Regression
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)
- Random Forest
- Tuned Random Forest (Grid Search + CV)

## Results (Test Set)
The tuned Random Forest achieved the best overall F1-score among tested models.

## Repository Contents
- `notebook.ipynb` — Full experiments (preprocessing, training, evaluation, tuning)
- `report.pdf` — Detailed project report (methods, tables, figures, discussion)

## How to Run
1. Open `notebook.ipynb` in Google Colab or Jupyter.
2. Install required packages (if needed): `scikit-learn`, `pandas`, `numpy`, `matplotlib`.
3. Run all cells.

## Author
Hasan Siraç Özbeyler
