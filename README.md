# Diabetes Prediction: A Machine Learning Analysis

**Team Project for ReDi School of Digital Integration**

## Introduction

Welcome to our team's collaborative journey into the realm of diabetes analysis! This project is the culmination of our efforts as part of the data analysis course at ReDi School of Digital Integration. Our objective of the project was to analyze a dataset describing various health characteristics of Native Indian females aged 21 and above, with a specific focus on predicting their health conditions as either diabetic or non-diabetic. The analysis aimed to employ data cleaning, descriptive statistics, data visualization, and classification algorithms to gain insights into the factors influencing diabetes. Additionally, the project sought to confirm hypotheses, identify key variables correlated with diabetic status, and ultimately select the best classification model for predicting the health condition.

**About the Dataset**

This dataset originates from the National Institute of Diabetes and Digestive and Kidney Diseases and aims to predict, based on diagnostic measurements, whether a patient has diabetes. The dataset is curated with specific constraints, focusing on females who are at least 21 years old and of Pima Indian heritage. For more details and to access the raw dataset, you can visit the [source on Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset).

### Key Steps in the Analysis:

1. **Data Cleaning:**
   - Replaced zero values.
   - Introduced three qualitative columns based on numeric features.
   - Addressed outliers using the winsorization technique.

2. **Data Visualization:**
   - Employed various techniques to explore variable characteristics and relationships.

3. **Correlation Analysis:**
   - Identified BMI, glucose level, and age as the top three variables most correlated with diabetic status.

4. **Statistical Analysis:**
   - Confirmed five out of six hypotheses, revealing a higher prevalence of diabetes in patients with obesity, senior patients, and those with above-average glucose and insulin levels.

5. **Classification Models:**
   - Utilized KNN, Decision Tree, and Logistic Regression to predict diabetic status.

### Model Selection:

- **Logistic Regression:**
  - Achieved the highest precision, recall, and f1-score.
  - Selected as the best model for predicting diabetic status.

### Overall Insights:

The analysis contributes valuable insights into the factors influencing diabetes, offering a nuanced understanding of the dataset. By employing a rigorous approach to cleaning, visualization, and modeling, this project enhances our knowledge of health conditions among Native Indian females. The selected Logistic Regression model stands out for its predictive accuracy, laying the groundwork for potential applications in real-world scenarios.

Feel free to explore the [Codebase](https://colab.research.google.com/drive/1_fJOUwwOA02bGm17EzGoEF3zTSYz6QCx?usp=sharing#scrollTo=KNOUjPJzXIct), review our findings, and contribute to the ongoing dialogue on diabetes prediction. 
