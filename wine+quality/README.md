# Wine Quality Prediction – Capstone Project

## Overview
This project predicts wine quality ratings using physicochemical features from red and white wines. The dataset was sourced from the UCI Machine Learning Repository. A Random Forest classifier was applied after thorough preprocessing, including feature scaling and one-hot encoding.

## Problem Statement
Winemakers need a reliable way to assess wine quality without expensive sensory panels. By predicting quality from chemical properties, we help streamline quality control and support decision-making in wine production.

## Methodology
- Combined red and white wine datasets
- Added `wine_type` feature and applied one-hot encoding
- Performed feature scaling using StandardScaler
- Trained a Random Forest classifier with tuned hyperparameters
- Evaluated performance using accuracy, precision, recall, and F1 score

## Results
- Accuracy: 83%
- F1 Score: 0.805
- Key influential features: Alcohol, Sulphates, Volatile Acidity

## Recommendations
1. Consider developing separate models for red and white wines.
2. Emphasize alcohol and sulphate content during production optimization.
3. Use model output to inform wine pricing and marketing strategies.

## Repository Structure
```
📁 capstone-project/
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_modeling_evaluation.ipynb
├── data/
│   └── winequality-*.csv
├── report/
│   ├── Capstone_Final_Report.pdf
│   └── model_metrics.txt
```

## References
- UCI Machine Learning Repository: Wine Quality Dataset
- Scikit-learn Documentation

## License
This project is for educational purposes under the Springboard Data Science Career Track.
