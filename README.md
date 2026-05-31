# WDBC Binary Classification Project

## Project Purpose
This project trains and compares multiple machine learning classifiers on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset to predict whether a tumor is malignant or benign.

## Dataset
- **Source:** scikit-learn built-in Breast Cancer dataset
- **Samples:** 569
- **Features:** 30 numeric features (e.g. mean radius, texture, perimeter)
- **Classes:** malignant, benign

## Requirements
- Python 3.x (Environment)
- scikit-learn
- matplotlib
- numpy


## How to Install Library Requirements
```
pip install -r requirements.txt
```

## How to Run the Code
```
python wdbc_classification.py
```

## Output Files
- `wdbc_classification_scatter.png` - Scatter plot of mean radius vs mean perimeter colored by class
- `wdbc_classification_matrix.png` - Confusion matrix of the best classifier

## Best Classifier Result
- **Best Classifier:** Decision Tree
- **Accuracy:** 1.0000 (on training data)
- **Classifiers tested:** SVM, Decision Tree, KNN, Random Forest
