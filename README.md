# NextGen_internship_week4
# Internship Weekly Report - Week 4

**Name:** Sandeep Ravaji Patel
**Domain:** Data Science
**Week Number:** Week 4

## Task Description

**Objective:** To understand the fundamentals of machine learning and apply them by building a simple linear regression model using Scikit-Learn, including data preprocessing, model training, and evaluation. [cite: 1, 2, 3, 4, 5, 6, 7]

## Tasks Completed:

**Machine Learning Basics:**
- Learned the difference between supervised and unsupervised learning. [cite: 2]
- Focused on linear regression as a foundational algorithm in supervised learning. [cite: 3]
- Understood concepts such as features, labels, training data, testing data, and overfitting. [cite: 4]

**Model Building:**
- Implemented Linear Regression using the 1000_Companies.csv dataset. [cite: 5]
- Preprocessed data (handled categorical features using Label encoding). [cite: 5]
- Split the dataset into training and testing sets using `train_test_split`. [cite: 6]
- Trained the linear regression model using Scikit-Learn's `LinearRegression()` class. [cite: 6]
- Predicted results and evaluated model performance using metrics like R² Score and Mean Squared Error (MSE). [cite: 7]

**Tools Used:**
- Scikit-Learn
- Pandas
- NumPy
- Jupyter Notebook

## Challenges Faced

1.  **Categorical Feature Handling:**
    -   Dataset included non-numeric features that couldn't be directly used in model training. [cite: 10]
    -   **Resolution:** Used `LabelEncoder()` from `sklearn.preprocessing` for Label encoding. [cite: 11]
2.  **Model Accuracy Variability:**
    -   Initial model showed low R² score. [cite: 11, 12]
    -   **Resolution:** Reviewed feature selection and normalized relevant features. [cite: 12]
3.  **Data Splitting Concerns:**
    -   Model was sensitive to random splits. [cite: 13]
    -   **Resolution:** Used `random_state` in `train_test_split` for reproducibility. [cite: 13]

## Learning Outcome

-   Understood the end-to-end workflow of building a regression model. [cite: 13, 14, 15]
-   Gained confidence using Scikit-Learn for model training and evaluation. [cite: 14]
-   Learned how to handle real-world data challenges like feature encoding and data splitting. [cite: 14]
-   Interpreted regression metrics like R² score and MSE for model assessment. [cite: 15]

## Next Steps

For **Week 5**, the focus will be on:
-   Working on classification and regression models like Decision Tree and Logistic Regression. [cite: 16, 17]
-   Evaluating models using accuracy and confusion matrix. [cite: 17]
-   Expanding understanding of model evaluation for classification problems. [cite: 17]

## Resources

-   ML Basics: Machine Learning with Python [cite: 18]
-   Scikit-Learn Documentation: https://scikit-learn.org/stable/ [cite: 18]
-   Dataset Used: 1000_Companies.csv [cite: 18]
