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
The model does a good job of catching most spam emails, though it still misclassifies a few. False negatives (spam marked as not spam) are the main area for improvement. Overall, Naïve Bayes proved to be a solid baseline for spam detection.  


