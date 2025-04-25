# Real Estate Price Classifier

A decision tree classifier implemented from scratch in Python using Pandas and SciPy.  
The model predicts whether a house price is high or low based on categorical real estate attributes.

## Features

- Entropy-based information gain for attribute selection
- Custom decision tree data structure
- Recursive tree training with threshold-controlled splitting
- 10-fold cross-validation for threshold optimization
- Evaluation on a test set

## Technologies
- Python 3
- Pandas
- NumPy
- SciPy

## Dataset
The classifier uses a categorical real estate dataset (`categorical_real_estate.csv`) with class labels and categorical features.

## How to Run

1. Install dependencies:
   ```pip install pandas numpy scipy```
2. Run the script:
   ```python decision_tree_learning_algorithm.py```
