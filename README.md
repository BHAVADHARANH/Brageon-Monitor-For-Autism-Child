Braegen Monitoring for Autism
=============================
Overview:
This project is designed for educational purposes, aiming to classify autism spectrum disorder (ASD) based on screening test responses. Using machine learning, the model predicts the likelihood of autism based on demographic and behavioral factors.

Features:
Data preprocessing (encoding, normalization)
Machine learning model (Random Forest Classifier)
Model evaluation (accuracy, classification report, confusion matrix)

Feature importance analysis:
Dataset:
The dataset used is Autism_Screening_Data_Combined.csv, containing:
A1 - A10: Binary responses to autism screening questions
Age, Sex, Jaundice, Family_ASD: Demographic and medical history details
Class: Target variable (Autism: YES/NO)

Installation:
Clone the repository:
git clone https://github.com/BHAVADHARANH/Brageon-Monitor-For-Autism-Child.git
cd Brageon-Monitor-For-Autism-Child

Install dependencies:
pip install -r requirements.txt

Usage:
Run the script to train and evaluate the model:
python autism_ml_model.py

Results:
Accuracy Score: Displays model performance
Classification Report: Precision, recall, F1-score
Confusion Matrix: Visualization of true vs. predicted values
Feature Importance: Identifies key factors in predictions

Dependencies:
-Python 3.x
-pandas
-scikit-learn
-matplotlib
-seaborn

Future Enhancements:
Hyperparameter tuning for better accuracy
Deploying as a web app (Flask/Django)
Integrating real-time monitoring for autism detection

License:
MIT License
