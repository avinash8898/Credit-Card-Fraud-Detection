**Credit Card Fraud Detection**

Project Overview

This project focuses on detecting fraudulent credit card transactions using Logistic Regression. The data used in this project is preprocessed with Principal Component Analysis (PCA) to reduce dimensionality and improve model performance. Additionally, various statistical analyses, such as calculating the mean and count of different features, were conducted to understand the data better.

##Dataset

The dataset contains credit card transactions with a mix of fraudulent and non-fraudulent activities. Key features include transaction amounts, times, and anonymized features derived from PCA.

Steps Followed

1. Data Preprocessing

PCA Transformation: The original features were transformed using PCA to reduce dimensionality and retain the most significant components.

Data Cleaning: Missing values were handled, and the dataset was normalized to prepare it for the Logistic Regression model.

2. Exploratory Data Analysis (EDA)

Statistical Analysis:

Mean: Calculated for each feature to understand the average transaction characteristics.

Count: Total number of transactions and the distribution of fraudulent vs. non-fraudulent transactions were analyzed.

Visualization: Histograms and box plots were created to visualize data distribution and detect any anomalies.

3. Model Building

Logistic Regression: A Logistic Regression model was chosen for its effectiveness in binary classification problems.

Model Training: The model was trained on the preprocessed dataset, with hyperparameters optimized for better performance.

Model Evaluation: The model's accuracy, precision, recall, and F1-score were evaluated to ensure robust detection of fraudulent transactions.

4. Results

The Logistic Regression model achieved significant accuracy in detecting fraudulent transactions.

PCA helped in reducing the complexity of the data and improving the model's computational efficiency.

**Conclusion**

This project demonstrates the use of Logistic Regression combined with PCA and statistical analysis to detect fraudulent credit card transactions effectively. The model's performance metrics indicate its potential for real-world application in financial fraud detection.

**Future Work**

Explore more advanced machine learning models like Random Forest or Neural Networks.

Implement real-time fraud detection systems.

Perform further feature engineering to improve model performance.

How to Run the Project

**Clone the repository:**

git clone https://github.com/avinash8898/Credit-Card-Fraud-Detection.git

**Navigate to the project directory:**

cd Credit-Card-Fraud-Detection


Run the Google Colaboratory or Python script for training the model.

Acknowledgements

The dataset used in this project was sourced from Kaggle, and we thank the contributors for providing a rich dataset for analysis and model building.
