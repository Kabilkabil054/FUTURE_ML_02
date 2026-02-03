# Support Ticket Classification System

## Description
This project implements a Machine Learning–based Support Ticket Classification
system using Natural Language Processing (NLP). The goal of the system is to
automatically analyze customer support messages and classify them into
appropriate categories such as Technical, Billing, or Account issues.
Additionally, the system predicts the priority level (High, Medium, Low) of
each ticket to help support teams respond more efficiently.

## Problem Statement
Customer support teams receive a large number of tickets daily. Manually
analyzing and prioritizing these tickets is time-consuming and error-prone.
This project solves the problem by using Machine Learning to automate ticket
classification and priority assignment.

## Dataset
- 120+ customer support tickets
- Columns:
  - ticket_text: Customer issue description
  - category: Type of issue (Technical, Billing, Account)
  - priority: Urgency level (High, Medium, Low)

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

## Methodology
1. Loaded and explored the dataset
2. Cleaned and preprocessed text data
3. Converted text into numerical features using TF-IDF
4. Trained Logistic Regression models for:
   - Ticket category classification
   - Priority prediction
5. Evaluated model performance using accuracy and classification reports
6. Tested the system with new, unseen support tickets

## Sample Prediction
Input: "payment failed and amount deducted"  
Output:
- Category: Billing  
- Priority: High

## Results
The model achieved high accuracy on the test dataset, demonstrating the
effectiveness of TF-IDF and Logistic Regression for text classification tasks.

## Conclusion
This project demonstrates an end-to-end NLP pipeline for automating customer
support ticket classification. The system can help organizations improve
response time and support efficiency.
