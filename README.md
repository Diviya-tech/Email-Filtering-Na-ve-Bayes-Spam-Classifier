![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-red?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)

# Email-Filtering-Naive-Bayes-Spam-Classifier

This project is about building a simple yet effective spam email classifier using the **Naïve Bayes algorithm**. The dataset contains emails labeled as either spam or not spam. I used **TF-IDF** to convert the raw email text into numerical features and then trained a **Gaussian Naïve Bayes model** to do the classification.  

## Why I Did This Project  
I wanted to get hands-on practice with natural language processing and machine learning, especially with text data. Spam detection is a classic problem that combines real-world relevance with clear evaluation metrics, so it felt like a great way to apply concepts like text preprocessing, feature extraction, and model evaluation. This notebook was also part of my learning journey to strengthen my data science and ML portfolio.  

## What’s Inside  
- Data preprocessing (cleaning text, handling missing values, vectorization with TF-IDF)  
- Training and testing using an 80/20 split  
- Model evaluation with a confusion matrix and classification report  
- Visualizations (bar chart of class distribution, confusion matrix heatmap)  

## Results

| Metric | Class 0 (Not Spam) | Class 1 (Spam) |
|--------|-------------------|----------------|
| Precision | 96% | 94% |
| Recall | 99% | 79% |
| F1-Score | 97% | 86% |
| **Overall Accuracy** | **95.5%** | |

**Confusion Matrix:**
- ✅ 492 legitimate emails correctly identified
- ✅ 81 spam emails correctly caught
- ⚠️ 22 spam emails missed (false negatives)
- ⚠️ 5 legitimate emails wrongly flagged as spam

**Key takeaway:** The model is great at protecting legitimate 
emails (99% recall) but misses about 1 in 5 spam emails. 
For a real-world filter, improving spam recall would be the 
next priority.  


