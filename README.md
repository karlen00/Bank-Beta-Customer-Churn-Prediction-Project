# Bank Beta Customer Churn Prediction Project

## Project Description

Bank Beta is experiencing a gradual decrease in the number of customers each month. It has been recognized that retaining existing loyal customers is more cost-effective than acquiring new ones. The task is to predict whether a customer will soon leave the bank using past customer behavior data and their contract termination history. The goal is to build a model with the highest possible F1 score, with a minimum requirement of 0.59 on the test dataset. Additionally, measure and compare the AUC-ROC metric with the F1 score.

## Project Instructions

### Step 1: Data Preparation

1. **Download and Load the Data:**
   - The dataset can be found in the file `/datasets/Churn.csv`.

2. **Features:**
   - `RowNumber`: Data index
   - `CustomerId`: Customer ID
   - `Surname`: Customer surname
   - `CreditScore`: Credit score
   - `Geography`: Country of residence
   - `Gender`: Gender
   - `Age`: Age
   - `Tenure`: Fixed deposit term (years)
   - `Balance`: Account balance
   - `NumOfProducts`: Number of bank products used by the customer
   - `HasCrCard`: Whether the customer has a credit card (1 - yes, 0 - no)
   - `IsActiveMember`: Whether the customer is an active member (1 - yes, 0 - no)
   - `EstimatedSalary`: Estimated salary

3. **Target:**
   - `Exited`: Whether the customer has left the bank (1 - yes, 0 - no)

4. **Data Preparation:**
   - Ensure all columns are in the correct data types.
   - Handle missing values if any.
   - Perform necessary feature engineering and preprocessing steps (e.g., encoding categorical variables, scaling numerical variables).

### Step 2: Exploratory Data Analysis (EDA)

1. **Class Balance Check:**
   - Check the distribution of the target variable (`Exited`).
   - Report the class imbalance if present.

2. **Initial Model Training:**
   - Train an initial model without considering class imbalance.
   - Briefly explain the findings and performance metrics.

### Step 3: Model Improvement

1. **Addressing Class Imbalance:**
   - Use at least two approaches to address class imbalance (e.g., oversampling, undersampling, SMOTE).
   - Split the data into training and validation sets.

2. **Model Training and Validation:**
   - Train multiple models with different algorithms and parameters.
   - Use the validation set to select the best model and parameter set.
   - Explain the findings and selected model/parameters.

3. **Model Optimization:**
   - Optimize the model performance while addressing class imbalance.
   - Ensure to evaluate different models and select the best performing one.

### Step 4: Final Testing

1. **Final Model Testing:**
   - Test the final model on the test dataset.
   - Report the F1 score and compare it with the required threshold of 0.59.

2. **Metric Comparison:**
   - Calculate the AUC-ROC metric for the final model.
   - Compare the AUC-ROC metric with the F1 score.
   - Provide insights and conclusions based on the comparison.

### Step 5: Documentation and Submission

1. **Documentation:**
   - Document the data preparation, EDA, model training, and improvement process.
   - Include explanations and insights for each step.

2. **Submission:**
   - Ensure all code and documentation are well-organized and formatted in a Jupyter Notebook.
   - Submit the final Jupyter Notebook for review.

## Conclusion

This README provides a structured approach to complete the customer churn prediction project for Bank Beta. Follow the steps outlined to achieve the desired model performance and document your findings comprehensively.

---
