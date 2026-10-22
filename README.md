# CreditWise – Intelligent Loan Approval System

## Overview
CreditWise is a machine learning project that predicts whether a loan application will be approved or rejected based on applicant information and financial attributes.

The project explores data preprocessing, exploratory data analysis, feature engineering, and classification algorithms to compare model performance.

## Objectives
- Clean and preprocess loan application data.
- Explore patterns and relationships in the dataset.
- Train multiple machine learning classification models.
- Evaluate models using standard classification metrics.
- Compare models to identify the most promising approach.

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook

## Workflow
1. Load and inspect the dataset.
2. Handle missing numerical and categorical values.
3. Perform exploratory data analysis and visualizations.
4. Encode categorical variables.
5. Analyze feature correlations.
6. Split the dataset into training and testing sets.
7. Scale features using StandardScaler.
8. Train and evaluate classification models.
9. Perform feature engineering and compare model performance.

## Machine Learning Algorithms
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The notebook identifies Logistic Regression as the best-performing model based on its comparison of precision, recall, and F1-score. Refer to the notebook outputs for the actual metric values.

## Project Structure

```text
CreditWise-Loan-Approval/
├── credit_wise.ipynb
├── loan_approval_data.csv
└── README.md
```

## How to Run
1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Ensure `loan_approval_data.csv` is in the same directory as the notebook.
4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `credit_wise.ipynb` and run the cells in order.

## Learning Outcomes
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature encoding and scaling
- Classification algorithms
- Model evaluation and feature engineering

## Future Improvements
- Tune model hyperparameters.
- Use cross-validation for more reliable model comparison.
- Build a simple web interface for loan approval predictions.

---
*This project was developed for learning and practicing data analysis and machine learning concepts.*
