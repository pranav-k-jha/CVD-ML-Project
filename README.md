# Predictive Analysis and Prevention of Cardiovascular Disease Using Machine Learning

**Abstract:**

Cardiovascular disease (CVD) is a significant global health issue, and early detection and intervention can potentially prevent many cases. This project focuses on using machine learning to analyze the Framingham Heart Study dataset to predict and prevent CVD. The approach is structured as follows:

1. **Data Acquisition**: Collecting a comprehensive dataset from diverse sources to ensure robust analysis.

2. **Data Filtering and Cleaning**: Addressing inconsistencies and missing values to enhance dataset reliability. Missing values were handled using imputation techniques, and outliers were removed to improve model performance.

3. **Data Transformation**: Converting data into a suitable format for analysis, including feature engineering and normalization. An interaction feature, `age_BMI_interaction`, was created to explore non-linear relationships.

4. **Exploratory Data Analysis (EDA)**: Identifying key features such as age, systolic and diastolic blood pressure, and glucose, which demonstrated significant correlations with the target variable, `TenYearCHD`.

5. **Model Building**: Implementing a Linear Regression model to predict the risk of heart disease. Despite achieving an accuracy of approximately 87%, the model faced challenges with imbalanced data, affecting performance in predicting positive cases of heart disease.

6. **Model Evaluation**: Assessing performance metrics revealed high accuracy but highlighted issues in detecting positive cases, as evidenced by low recall, precision, and F1 score for the positive class.

**Recommendations:**

- **Model Improvement**: Consider more robust models such as Logistic Regression, Random Forest, or Gradient Boosting. Techniques like SMOTE (Synthetic Minority Over-sampling Technique) could also help address dataset imbalance.

- **Feature Exploration**: Further investigate additional features or interaction terms that might enhance predictive power. Explore feature scaling and normalization for potential performance improvements.

Overall, the project provides valuable insights and a preliminary predictive model for heart disease, but further refinement and exploration are needed to achieve a more balanced and accurate model.
