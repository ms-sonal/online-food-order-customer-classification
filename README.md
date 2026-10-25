# Online Food Order Customer Classification

A machine learning project to classify customers as **Frequent, New, or Regular** using demographic and socioeconomic features.

## Project Overview

This project explores customer data and builds machine learning classification models to predict customer type.

## Objectives

- Understand the dataset through Exploratory Data Analysis (EDA).
- Clean and preprocess data.
- Encode categorical features and handle missing values.
- Train and compare different classification algorithms.
- Evaluate model performance using cross-validation and test-set metrics.

## Dataset

- **Total records:** 388
- **Target variable:** `Customer Type`
- **Classes:** Frequent, New, Regular
- **Features:** Age, gender, marital status, occupation, monthly income, educational qualifications, and family size.

## Machine Learning Workflow

1. Data loading and cleaning
2. Exploratory Data Analysis
3. Feature selection
4. Train-test split
5. Data preprocessing using `ColumnTransformer` and `Pipeline`
6. Model comparison using 5-fold cross-validation
7. Final model evaluation

## Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Results

The Decision Tree Classifier with `max_depth=2` was selected as the final model.

| Metric | Result |
|---|---:|
| Cross-validation accuracy | 100% |
| Test accuracy | 100% |
| Test records | 78 |

The model achieved perfect scores on the evaluated data. However, the dataset is relatively small, and further evaluation on independent data is needed to assess generalization.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## How to Run

1. Open the notebook `Online_Food_Order_Customer_Classification.ipynb`.
2. Open it in Google Colab.
3. Provide the dataset at the path expected by the notebook.
4. Run the notebook cells in order.

## Key Learnings

- Data preprocessing and feature encoding
- Building machine learning pipelines
- Comparing classification algorithms
- Using cross-validation
- Evaluating classification models with accuracy, confusion matrix, precision, recall, and F1-score

## Future Improvements

- Validate the model on additional independent data.
- Investigate the unusually high evaluation scores.
- Test performance on new customer records.

---

**Author:** Sonal  
**Project Type:** Beginner Machine Learning Project
