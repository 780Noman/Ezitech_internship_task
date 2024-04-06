# Email Spam Classification Project

## Overview

This project aims to classify emails into two categories: 'ham' (non-spam) and 'spam'. It involves the following steps:

1. Data Preparation:
   - Import necessary libraries.
   - Load the email dataset from a CSV file.
   - Handle missing values and duplicates.
   - Explore the data to understand its distribution.

2. Data Splitting:
   - Split the dataset into training and testing sets for model evaluation.

3. Feature Extraction:
   - Use CountVectorizer to convert text messages into numerical feature vectors.

4. Model Training and Evaluation:
   - Train three classification models: Naive Bayes, Decision Tree, and Logistic Regression.
   - Evaluate the models using accuracy, precision, recall, and F1 score metrics.
   - Generate confusion matrices to visualize model performance.

5. Model Comparison:
   - Compare the performance of the three models based on their accuracy scores.

## File Structure

- `email.csv`: Contains the email dataset with 'Message' and 'Category' columns.
- `spam-email-classification.py`: Python script containing the code for data preparation, model training, evaluation, and comparison.

## Usage

1. Mount Google Drive:
   - Run the `drive.mount('/content/drive')` command to mount your Google Drive.
2. Run the Main Script:
   - Execute the `main.py` script to perform the following tasks:
     - Load the email dataset.
     - Split the data into training and testing sets.
     - Train and evaluate the three classification models.
     - Compare the models based on accuracy.
3. View Results:
   - The script prints the accuracy, precision, recall, and F1 score for each model.
   - Confusion matrices are generated to visualize the models' performance.
   - A sorted list of models based on accuracy is displayed.

## Conclusion

This project demonstrates how to classify emails spam or ham
 using different machine learning models. The results show that Logistic Regression achieves the highest accuracy for this particular dataset.
