# Fake News Detection and Evaluation with Confusion Matrix

## Project Overview
This project was completed as part of the IDEAS TIH Summer Internship 2026.

The objective of the project is to build a machine learning model that can classify news articles as real or fake using text processing and classification techniques.

## Dataset
The project uses:
- fake.csv
- true.csv

These datasets were provided by the internship organizers.

## Methods Used
- Data Loading and Preprocessing
- Text Cleaning
- TF-IDF Vectorization
- Logistic Regression
- Decision Tree Classification
- Grid Search Hyperparameter Tuning

## Results
### Logistic Regression
Accuracy: ~99%

### Decision Tree
Accuracy: 99.71%

### Best Hyperparameters
```python
{'C': 10, 'solver': 'liblinear'}
