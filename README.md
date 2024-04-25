# README for Moonboard Climbing Difficulty Classification Project
 ## Project Overview
 The purpose of this machine learning project is to grade bouldering difficulties on the Moonboard, a standardised training wall that climbers utilise all around the world, objectively. Traditional climbing difficulty grading is subjective, which affects training and fair competition. The objective of the research is to create a grading system that is standardised and reproducible by using a classification model that is trained on large amounts of Moonboard data.
 ## Best Performing Model: XGBoost Final
 The XGBoost Final notebook represents the final version of the XGBoost model, the best model found. The model has been manually tuned using insights found in development models explained in the documentation to identify the best parameters, using borderline smote sampling to handle class imbalance. the notebook includes the performance metrics of the best performing model and a confusion matrix to visually represent its performance on the classes used. It is the product of extensive experimentation and iteration across various models available in the Development Notebooks folder. This model stands out due to its robust performance against the dataset.
 ## Data Collection
 The dataset comprises climb sequences and hold coordinates from the Moonboard enhanced by adding grip orientation and hold type. The grip orientation is based on official Moonboard specifications, while hold type is determined by consensus among experienced climbers.
 ## Development Process
 The model development was iterative, documented through version-controlled notebooks on GitHub. Initial models laid the groundwork, with specialized notebooks for XGBoost, SVM, and Gradient Boosting Machine to fine-tune the best performers.
 ## Installation and Usage
 Refer to the project folder for the datasets:
 
allclimbs1repeatormore.csv
updatedfeatures.csv

Install the required libraries listed in the final notebooks imports section to replicate the model training and evaluation.

