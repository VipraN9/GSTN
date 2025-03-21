# GSTN
 Developed for the GSTN hackathon organized by Government of India.
 
A classification solution for a comprehensive  data set containing approximately 900,000 records, each with around 21 attributes and target variables. This data is anonymized, meticulously labeled, and includes training, testing, and a non-validated subset reserved specifically for final evaluations by the GSTN.

# Approach
Data Preparation:

The initial phase involved loading the dataset and handling missing values through imputation.
Data was standardized to ensure all features contributed equally to the model training.
Model Selection:
Two primary models were developed:
● Neural Network: A feedforward neural network using Keras was constructed for its
flexibility in capturing complex patterns.
● Random Forest Classifier: This ensemble method was chosen for its robustness against
overfitting and ability to handle high-dimensional data.

# Training and Evaluation:
Each model was trained on a subset of the data, followed by evaluation using accuracy, F1 score,
and ROC AUC metrics. Hyperparameter tuning was performed using RandomizedSearchCV for
the Random Forest model to optimize performance.
Feature Importance Analysis:
The importance of features was assessed using the Random Forest model, which provided
insights into which variables significantly impacted predictions.
Visualization:
Various visual aids, including confusion matrices and feature importance plots, were created to
support findings and enhance understanding.

$ Findings
Model Performance:

The Neural Network achieved an accuracy of approximately 95% on the test set.
The Random Forest Classifier outperformed with an accuracy of around 98%, demonstrating its
effectiveness in handling the dataset.
Feature Importance:
Key features influencing predictions were identified, allowing for targeted improvements in data
collection or feature engineering in future iterations.



