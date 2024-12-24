# Spam-Detection-for-YouTube-Comments

Title: Spam Detection in YouTube Comments Using Machine Learning  

YouTube's comment sections are often flooded with spam, including phishing links, scams, and irrelevant advertisements, disrupting user experience and reducing platform integrity. This research addresses the challenge of detecting and mitigating spam in YouTube comments through machine learning techniques.  

Objectives  
The primary aim of this research is to develop and evaluate robust machine learning models for detecting spam in YouTube comments. It involves transforming raw text data into meaningful numerical features using Term Frequency-Inverse Document Frequency (TF-IDF) vectorization, which highlights the importance of words in spam detection.  

Methods  
The project evaluates the following machine learning algorithms to classify comments as spam or non-spam:  
- Logistic Regression (LR)  
- Naive Bayes (NB)  
- Random Forest (RF)  
- Support Vector Classifier (SVC)  
- Decision Tree (DT)  
- K-Nearest Neighbors (KNN)  
- Multi-layer Perceptron (MLP)  
- Voting Classifier (integrating predictions from multiple models for improved performance)  

Evaluation Metrics  
The models are assessed on the following performance metrics:  
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- AUC (Area Under the ROC Curve)  
- AUC-PR (Area Under the Precision-Recall Curve)  
- Error Rate  

Key Findings  
- Support Vector Classifier (SVC)achieved the best results, with an accuracy of 91.60%, precision of 91.47%, recall of 92.19%, and F1 score of 91.83%. It also delivered high AUC (96.02%) and AUC-PR (94.32%) scores, proving its effectiveness in distinguishing spam from non-spam.  
- Voting Classifier, combining multiple models, provided strong results, achieving 90.47% accuracy and an F1 score of 90.92%.  

Contributions  
This research highlights the superiority of the SVC model in spam detection for YouTube comments and provides insights into the performance of various machine learning techniques in this unique and challenging context. These findings contribute to developing advanced spam detection systems, enhancing user experience, and improving platform security.  

Repository Contents  
- Code: Python scripts for preprocessing, model training, and evaluation.  
- Dataset: Processed dataset of YouTube comments with spam labels.  
  

This repository is a comprehensive resource for researchers and developers interested in text classification, spam detection, and improving online platform security.  

