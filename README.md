# Car_Purchase_Amount-
Car_Purchase_Amount_Prediction

### 1. Introduction
- The objective of this project is to develop a machine learning model, specifically utilizing Artificial Neural Networks (ANNs), to predict the total dollar amount a customer is willing to pay for a car.
- This prediction will be based on various customer attributes such as gender, age, annual salary, credit card debt, and net worth. The problem is formulated as a regression task, where the target variable is the continuous car purchase amount.

### 2. Data Preprocessing
##### Input Features:

- Gender
- Age
- Annual Salary
- Credit Card Debt
- Net Worth

##### Target Variable:
- Car Purchase Amount

##### Preprocessing Steps:

- Encoding Categorical Data: Convert the categorical feature "Gender" into numerical representation (e.g., 0 for female, 1 for male).
- Normalization: Scale continuous features (Annual Salary, Credit Card Debt, and Net Worth) to a common range (e.g., 0 to 1) to improve model convergence and performance.
- Data Splitting: Divide the dataset into training and testing sets to evaluate model performance on unseen data.

### 3. Model Building
#### ANN Architecture:

- Input Layer: 5 neurons (corresponding to the 5 input features)
- Hidden Layers:
- Layer 1: 25 neurons with ReLU activation
- Layer 2: 10 neurons with ReLU activation
- Output Layer: 1 neuron (predicting the car purchase amount)
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam

### 4. Training Process
- Train the model for 25 epochs.
- Monitor training and validation loss during each epoch to assess model performance.

### 5. Model Evaluation
- Evaluation Metric: Mean Squared Error (MSE)
- Calculate MSE on both training and testing sets to evaluate model performance.

### 6. Predictions

##### Test Case:

- Gender: Male
- Age: 50
- Annual Salary: $50,000
- Credit Card Debt: $10,985
- Net Worth: $629,312

- Prediction: The model predicts a car purchase amount of $226,242.23 for this customer.
  
### 7. Conclusion
- The ANN model successfully predicts car purchase amounts based on given customer attributes.
- Further hyperparameter tuning and exploration of different network architectures can potentially improve model accuracy and generalization.
