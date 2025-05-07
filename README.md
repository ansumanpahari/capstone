# Machine Learning and Artificial Intelligence - Capstone Project
**What determines the Breast Cancer is Maligment or Benign?**

## Data
**Source**

    https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
## Technique
The following Classification Tenchiques will be used for modeling
    K-NN
    Logistic Regression
    Decision Tree
    Support Vector Machine

## Expected Results
The Classification model will predict two categories Malignment and Benign based on test data.

    Malignment - Breast cancer is defined as malignment.
    Benign - Breast cancer is defined as benign.

## Why this question is important
The model is used to predict the nature of breast cancer. It helps with the diagnosis and will help patients to decide on further treatment.

### Best Model
    - SVC Model
        - Because of High Accuracy, Precision and Recall value.
### Limitation
    - Data set is relativly small because of (mem/cpu) limitation
    - Couldn't go higher SVC Hyperparameter because of limited resource (mem/cpu)
### File Structure
- images folder - Contains images
- prompt Jupyter file - The main juypter file. Contains code.