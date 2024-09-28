Oil Spill Detection using AIS and Satellite Datasets
Overview:
This repository contains the demo model for detecting oil spills in marine environments using Automatic Identification System (AIS) and satellite datasets. Developed for the Smart India Hackathon (SIH) 2024, our objective is to create an efficient system that identifies and monitors oil spill incidents to mitigate environmental impact.

Dataset:
The datasets used in this project were primarily sourced from VesselFinder. Due to the nature of the data being paid, we manually collected additional AIS data for our training model to enhance the detection capabilities.

Technology Stack:

XGBoost
Python
NumPy
Pandas
Scikit-learn
Objective: To build a reliable system that detects oil spills using AIS and satellite datasets, providing essential insights for environmental protection.

Usage:
To run the demo model, ensure you have the required packages installed. You can install them using pip:
pip install xgboost pandas scikit-learn flask numpy
Warning Explanation:
While running the demo model, you may encounter the following warning:
C:\Users\Sayed\AppData\Local\Programs\Python\Python39\lib\site-packages\sklearn\metrics\_classification.py:409: UserWarning: A single label was found in 'y_true' and 'y_pred'. For the confusion matrix to have the correct shape, use the 'labels' parameter to pass all known labels.
Reason for the Warning:
This warning indicates that during the evaluation of the model, only one class label was present in both the true and predicted values. This can happen when the dataset is small or imbalanced, resulting in the model being trained primarily on one class.

Future Improvements:
As we utilize a larger and more balanced dataset, this issue is expected to be resolved. The model will then be able to recognize and predict multiple class labels effectively.

Conclusion:
This project serves as a foundational step toward creating an automated oil spill detection system.
