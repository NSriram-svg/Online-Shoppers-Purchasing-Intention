# Online Shoppers' Purchasing Intention Prediction Using Machine Learning

## Project Overview
This project uses machine learning classification algorithms to predict whether an online shopping session will result in a purchase. The goal is to analyze visitor behavior and identify patterns associated with purchasing intention.

## Objectives
- Analyze online shopping session data.
- Preprocess and prepare data for machine learning.
- Handle class imbalance using SMOTE.
- Compare multiple classification algorithms.
- Evaluate model performance using classification metrics.

## Dataset
The dataset is named `online_shoppers_intention.csv`.

It contains information about online shopping sessions, including page visits, bounce rates, exit rates, visitor type, month, and revenue.

**Target variable:** `Revenue`
- `True`: The session resulted in a purchase.
- `False`: The session did not result in a purchase.

Check the dataset's licence before redistributing it. If you cannot confirm permission, obtain the dataset from an authorized source and keep it out of the public repository.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn

## Machine Learning Algorithms
The project compares the following classification algorithms:
1. Random Forest Classifier
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Ridge Classifier
5. Bernoulli Naive Bayes
6. Support Vector Classifier (SVC)

## Project Workflow
1. Load the dataset.
2. Preprocess the data.
3. Perform feature engineering.
4. Split the data into training and testing sets.
5. Apply preprocessing and class balancing.
6. Compare classification models.
7. Evaluate the selected model.

## Evaluation Metrics
- Accuracy
- ROC-AUC
- F1-score
- Precision
- Recall
- Classification report

## Project Structure
```text
Online-Shoppers-Purchasing-Intention/
├── online_shoppers_intention.csv
├── online_shoppers_intention_fixed.py
├── requirements.txt
├── README.md
└── reports/
    └── Online_Shoppers_Intention_Project_Report.docx
```

## Installation and Execution

### 1. Install the required libraries
```bash
pip install -r requirements.txt
```

### 2. Run the Python program
Make sure the Python script and dataset are in the same folder, then run:

```bash
python online_shoppers_intention_fixed.py
```

## Results
The program compares classification models and displays evaluation metrics. Actual results should be recorded here after successfully running the final version of the code.

## Future Improvements
- Improve model performance through hyperparameter tuning.
- Explore additional feature engineering techniques.
- Compare more classification algorithms.
- Develop a simple web application for predictions.

## Author
Add your name here.

## Disclaimer
This project is intended for educational and learning purposes.