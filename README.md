# Car_Purchase_Amount-
Car_Purchase_Amount_Prediction

Car Purchase Amount Predictions Using Artificial Neural Networks (ANNs)

1. Introduction
The goal of this project is to build a machine learning model using Artificial Neural Networks (ANNs) to predict the total dollar amount a customer is willing to pay for a car based on specific attributes like:

Gender
Age
Annual Salary
Credit Card Debt
Net Worth
This is a regression problem where the target variable is the Car Purchase Amount.

2. Data Preprocessing
Input Features: Gender, Age, Annual Salary, Credit Card Debt, and Net Worth.
Target Variable: Car Purchase Amount.
Preprocessing Steps:
Encoding categorical data like Gender.
Normalizing continuous features (Annual Salary, Credit Card Debt, and Net Worth) for better model performance.
Splitting the dataset into training and testing sets for validation purposes.
3. Model Building
The ANN model was built using Keras’ Sequential API.
Network Architecture:
Input Layer: 5 features (Gender, Age, Annual Salary, Credit Card Debt, Net Worth).
Hidden Layers:
Layer 1: 25 neurons, ReLU activation.
Layer 2: 10 neurons, ReLU activation.
Output Layer: 1 neuron (for predicting the car purchase amount).
Loss Function: Mean Squared Error (MSE).
Optimizer: Adam.
4. Training Process
The model was trained for 25 epochs.
Loss was recorded for both training and validation datasets during each epoch.
The model showed improvement in training performance as the loss decreased over time.
5. Model Evaluation
Evaluation Metric: Mean Squared Error (MSE) was used to evaluate the model.
Final Training Loss and Validation Loss (exact values should be retrieved from the notebook).
The model’s predictions were tested using the unseen test data to evaluate its ability to generalize.
6. Predictions
A specific test case was used:
Gender: Male
Age: 50
Annual Salary: $50,000
Credit Card Debt: $10,985
Net Worth: $629,312
Prediction: The model predicted a car purchase amount of $226,242.23 for this customer.
7. Conclusion
The ANN model successfully predicted the car purchase amount based on customer attributes.
The model can be improved with further hyperparameter tuning to increase accuracy and decrease error.
