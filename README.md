# Email Spam Detection using Machine Learning

## Overview
The **Email Spam Detection System** is a machine learning project that classifies emails as **Spam** or **Not Spam** based on their content.  
It uses Natural Language Processing (NLP) and machine learning algorithms to automatically detect and filter unwanted emails.

## Objective
To build a machine learning model that can accurately identify spam emails by analyzing the textual content of messages.

## Algorithms Used
- Naive Bayes  
- Support Vector Machine (SVM)  

Both models were trained, evaluated, and compared for performance. The best-performing model was selected for the final prediction.

## Dataset
The dataset used is the **Spam Email Classification Dataset** from Kaggle.  
It contains thousands of email messages labeled as **spam** or **ham** (not spam).

## Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

## Steps Involved
1. Data loading and preprocessing  
2. Text cleaning (removal of punctuation, numbers, and special characters)  
3. Tokenization and stopword removal  
4. Converting text into numerical vectors using **TF-IDF Vectorizer**  
5. Splitting data into training and testing sets  
6. Training models using **Naive Bayes** and **SVM**  
7. Evaluating model performance using accuracy, confusion matrix, and classification report  
8. Selecting and saving the best model for spam detection  

## Results
Both **Naive Bayes** and **SVM** achieved high accuracy in classifying emails.  
Naive Bayes performed exceptionally well due to its simplicity and efficiency in handling text data.

## Future Enhancements
- Use deep learning models such as **LSTM** or **BERT** for better accuracy  
- Build a **Streamlit web app** for real-time spam detection  
- Integrate with email platforms to filter messages automatically
