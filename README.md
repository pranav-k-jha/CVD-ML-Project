# Cardiovascular Disease Prediction Using Machine Learning

## Project Overview
In this analysis, we examined the Framingham Heart Study dataset to understand and predict cardiovascular disease risk. The primary goal was to identify key features associated with heart disease and build a predictive model to enhance early detection and intervention.

### Dataset
- **Data Source:** [Kaggle Link](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)

### Feature Analysis
- **Key Features Identified:** Age, Systolic Blood Pressure (sysBP), Diastolic Blood Pressure (diaBP), and Glucose exhibited significant correlations with the target variable `TenYearCHD`. These features are crucial for predicting heart disease risk.

### Data Cleaning
- **Handling Missing Values:** Missing values were imputed using median values for `age` and mean values for `sysBP`, `diaBP`, and `glucose`.
- **Outlier Removal:** Outliers were identified and removed to improve dataset quality and model performance.

### Feature Engineering
- **Interaction Feature:** An interaction term, `age_BMI_interaction`, was created to investigate potential non-linear relationships between age and BMI.

### Model Building
- **Model Used:** A Linear Regression model was trained on the dataset.
- **Performance:** The model achieved an accuracy of approximately 87%. However, it faced challenges due to the imbalanced nature of the dataset, leading to lower performance in predicting positive cases (i.e., individuals with heart disease).

### Model Evaluation
- **Performance Metrics:**
  - **Accuracy:** High accuracy was observed.
  - **Challenges:** Low recall, precision, and F1 score for the positive class highlighted difficulties in detecting individuals with heart disease.
  - **ROC Curve:** The ROC curve analysis provided insights into the model's performance across different thresholds, with an area under the curve (AUC) reflecting overall model capability.

## Recommendations for Model Improvement

### Model Improvement
- **Explore Advanced Algorithms:** Consider utilizing more robust models such as Logistic Regression, Random Forest, or Gradient Boosting. These algorithms are often better equipped to handle imbalanced datasets and may provide improved performance.
- **Data Balancing Techniques:** Incorporate techniques like SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset and enhance the model's ability to correctly identify positive cases.

### Feature Exploration
- **Additional Features:** Investigate additional features or interaction terms that could improve the predictive power of the model.
- **Feature Scaling and Normalization:** Experiment with scaling and normalization techniques to potentially enhance model performance and stability.

## Conclusion
The analysis provided valuable insights into cardiovascular disease risk and developed a foundational predictive model. However, further refinement and exploration are needed to achieve a more balanced and accurate model. Implementing advanced algorithms, addressing data imbalance, and exploring additional features will contribute to enhancing the model's effectiveness in predicting cardiovascular disease.
