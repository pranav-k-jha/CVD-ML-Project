# Cardiovascular Disease Prediction Using Machine Learning

## Project Overview
In this analysis, we explored the Framingham Heart Study dataset to understand and predict the risk of cardiovascular disease. The primary goal was to identify key features associated with heart disease and to build a predictive model.

## Key Findings

### Dataset
- **[Data Source References: Kaggle Link](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)**

### Feature Analysis
- **Age, Systolic Blood Pressure (sysBP), Diastolic Blood Pressure (diaBP), and Glucose:** These features showed significant correlations with the target variable `TenYearCHD`, highlighting their importance in predicting heart disease.

### Data Cleaning
- **Missing Values:** Addressed by imputing with median or mean values as appropriate.
- **Outlier Removal:** Performed to enhance dataset quality and improve model performance.

### Feature Engineering
- **Interaction Feature:** Created `age_BMI_interaction` to explore potential non-linear relationships between age and BMI.

### Model Building
- **Model Used:** Implemented a Linear Regression model.
- **Performance:** Achieved approximately 87% accuracy, but struggled with the imbalanced nature of the dataset, resulting in lower performance in predicting positive cases (individuals with heart disease).

### Model Evaluation
- **Metrics:** High accuracy was observed, but challenges in detecting positive cases were evident, with low recall, precision, and F1 score for the positive class.

## Recommendations for Model Improvement

### Model Improvement
- **Explore Robust Models:** Consider using algorithms such as Random Forests or Gradient Boosting that are better suited for handling imbalanced datasets.
- **Address Data Imbalance:** Utilize techniques like SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset and improve the model's ability to detect positive cases.

### Feature Exploration
- **Investigate Additional Features:** Further explore other features or interaction terms to enhance predictive power.
- **Apply Feature Scaling and Normalization:** Experiment with scaling and normalization techniques to potentially improve model performance.

Overall, while the analysis has provided valuable insights and a foundational predictive model, further refinement and exploration are necessary to develop a more balanced and accurate model for cardiovascular disease prediction.

