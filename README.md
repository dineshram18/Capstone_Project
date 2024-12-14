
# Conclusive Report

## Data Wrangling

1. **Initial Data Overview:**
    - The dataset contains 520 rows and 17 columns.
    - Columns include demographic and symptom-related information, with a target class indicating diabetes status.

2. **Missing Values:**
    - No missing values were found in the dataset.

3. **Duplicate Rows:**
    - 269 duplicate rows were identified and removed, leaving 251 unique rows.

4. **Data Types:**
    - 'Age' is an integer, and all other columns are categorical (object type), which is appropriate for the data.

## Data Analysis

1. **Distribution of Age:**
    - The age distribution was visualized using a histogram.
    - The dataset contains a wide range of ages, with a noticeable concentration in the middle age group.

2. **Gender Distribution:**
    - The gender distribution was visualized using a count plot.
    - The dataset has a balanced distribution of male and female participants.

3. **Diabetes Class Distribution:**
    - The distribution of diabetes class was visualized using a count plot.
    - The dataset contains a higher number of positive diabetes cases compared to negative cases.

4. **Distribution of Key Features by Class:**
    - The distribution of key features such as 'Age', 'Polyuria', 'Polydipsia', 'sudden weight loss', and 'weakness' was visualized by diabetes class.
    - These visualizations help in understanding the relationship between these features and the target variable.

## Feature Importance

1. **Random Forest Feature Importance:**
    - The feature importance was calculated using a Random Forest classifier.
    - The top 5 most important features are 'Polyuria_Yes', 'Polydipsia_Yes', 'Age', 'Gender_Male', and 'partial paresis_Yes'.

2. **Logistic Regression Coefficients:**
    - The coefficients of the logistic regression model were analyzed.
    - The features with the highest positive coefficients are 'Polydipsia_Yes', 'Polyuria_Yes', and 'Genital thrush_Yes'.
    - The features with the highest negative coefficients are 'Gender_Male', 'Itching_Yes', and 'delayed healing_Yes'.

## Model Performance

1. **Model Comparison:**
    - Several models were trained and evaluated, including Logistic Regression, Random Forest, Decision Tree, SVM, and KNN.
    - The Random Forest model achieved the highest accuracy of 92.16%.
    - The SVM model had the lowest accuracy of 68.63%.

2. **Logistic Regression Performance:**
    - The logistic regression model achieved an accuracy of 72.55%.
    - The precision, recall, and F1 score were also calculated to evaluate the model's performance.

## Summary Statistics

1. **Age Statistics by Class:**
    - The summary statistics for age by diabetes class were calculated.
    - The mean age for negative cases is 46.36 years, while the mean age for positive cases is 49.07 years.

## Conclusion

- The dataset was successfully cleaned and analyzed, with no missing values and duplicate rows removed.
- Key features influencing diabetes status were identified using feature importance and logistic regression coefficients.
- The Random Forest model was the best-performing model, achieving the highest accuracy.
- Further analysis can be conducted on the cleaned dataset to explore more complex relationships and improve model performance.
