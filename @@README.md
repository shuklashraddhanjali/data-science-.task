# data science task report

**Dataset Exploration and Model Development**


**1. Dataset Exploration:**

To perform dataset exploration on the Iris dataset from sklearn.datasets, we will follow these steps:

Step1:- Load the Iris dataset.

Step2:- Display the first five rows of the dataset.

Step3:- Check the dataset’s shape.

**Outcome:**

A clear overview of the dataset’s features, their values, and statistical measures to understand data distribution.

**2. Data Splitting:**

To split the Iris dataset into training and testing sets with an 80-20 split, we can use the train_test_split function from sklearn.model_selection. 
This function will randomly split the data into two sets: one for training the model and one for testing it.

Here's how to perform the split:

Step1:- Load the Iris dataset (as done previously).

Step2:- Split the data into features (X) and target (y).

Step3:- Use train_test_split to split the data into training and testing sets.

Step4:- Print the number of samples in both the training and testing sets.

**Outcome:**

Separate training and testing datasets to ensure that the model is evaluated on unseen data, which aids in validating model performance.

**3. Linear Regression:**

To perform linear regression using a dataset with the features YearsExperience and Salary, we can follow these steps:

Step1:- Load the dataset

Step2:- Preprocess the data (if needed, such as splitting the data into train and test sets)

Step3:- Fit a linear regression model using the training data

Step4:- Make predictions on the test set

Step5:- Evaluate the model using Mean Squared Error (MSE)

**Outcome:**

A trained linear regression model with an evaluation of prediction accuracy based on MSE, indicating the model’s prediction error on the test set.
