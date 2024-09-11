Breast Cancer Prediction using Machine Learning
_______________________________________________
Overview~

This project aims to develop a machine learning model to predict breast cancer diagnosis. By analyzing patient data, the model classifies whether a tumor is malignant or benign based on various medical features.

Dataset~

The dataset contains numerical measurements of tumor characteristics for 569 patients, along with a diagnosis label indicating whether the tumor is malignant or benign. The features describe various aspects of the tumors, such as their size, shape, and texture, across different measurement types (mean, standard error, and worst case).

Project Workflow~

1.	Exploratory Data Analysis (EDA)

  o	Analyzed the data distribution and identified patterns between tumor characteristics and diagnoses.
  
  o	Visualized key statistical relationships to understand the underlying structure of the data.
  
2.	Data Preprocessing~

  o	Addressed missing or inconsistent data.
  
  o	Scaled the feature values to ensure better model performance.
  
  o	Transformed categorical values into a format suitable for machine learning algorithms.
  
3.	Model Building~

  o	Tested a variety of machine learning algorithms, including:
  
  .	Logistic Regression
  
  o	Evaluated model performance using accuracy, precision, recall, and F1-score metrics.
  
4.	Model Evaluation~

  o	Implemented cross-validation to enhance model reliability.
  
  o	Assessed models using confusion matrix, classification reports, and ROC-AUC curves to evaluate performance comprehensively.

5.	Results~
   
  o	Achieved an accuracy of 97% with the Logistic Regression model.
  
