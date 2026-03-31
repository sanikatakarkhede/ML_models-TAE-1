# Email Spam Detection using Machine Learning

# Overview

This project focuses on detecting whether an email is **Spam** or **Not Spam (Ham)** using various Machine Learning algorithms.
The system processes text data and classifies messages with high accuracy.



# Objectives

* To classify emails as spam or not spam
* To apply different Machine Learning models
* To compare model performance
* To understand text preprocessing using TF-IDF


# Dataset

* Source: CSV file (spam.csv)
* Features:

  * `message` → Email text
  * `label` → Spam (1) / Not Spam (0)



# Technologies Used

* Python 
* Pandas
* Scikit-learn
* Matplotlib

---

# Methodology

1. Data Collection
2. Data Cleaning
3. Text Vectorization (TF-IDF)
4. Train-Test Split (80:20 & 70:30)
5. Model Training
6. Evaluation
7. Prediction

---

# Models Used

* Logistic Regression
* Decision Tree
* Naive Bayes
* Support Vector Machine (SVM)
* Random Forest
* K-Nearest Neighbors (KNN)



# Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix


# Results

* Naive Bayes performed best for text classification
* SVM achieved high accuracy
* Random Forest provided stable performance
* KNN was slower for large datasets



 # Key Concepts

* TF-IDF converts text into numerical format
* Supervised learning is used
* Classification problem



# How to Run

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas scikit-learn matplotlib
   ```
3. Run the Python file:

   ```bash
   python spam_detection.py
   ```



# Sample Output


Message: Congratulations! You won a free ticket  
Prediction: SPAM  

Message: Hey, are we meeting today?  
Prediction: NOT SPAM  


 # Conclusion

Machine Learning models can effectively detect spam emails.
Naive Bayes and SVM showed the best performance for this dataset.

 # Future Scope
* Real-time spam detection system
* Use of Deep Learning (LSTM, NLP models)
* Integration with email services


# Acknowledgement
This project was developed as part of Machine Learning coursework.
