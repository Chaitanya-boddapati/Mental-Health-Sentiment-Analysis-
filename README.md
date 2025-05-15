# Mental-Health-Sentiment-Analysis-
This project leverages Natural Language Processing (NLP) and Machine Learning (ML) techniques to perform sentiment analysis on mental health-related content. The goal is to classify posts and comments from online forums, blogs, and social media into different mental health states such as Normal, Anxiety, Bipolar, Depression, and Suicidal Messages
Here’s a concise **GitHub project description** for your **Mental Health Sentiment Analysis** project:

---

## **Mental Health Sentiment Analysis Using NLP & Machine Learning**

This project leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to perform sentiment analysis on mental health-related content. The goal is to classify posts and comments from online forums, blogs, and social media into different **mental health states** such as **Normal**, **Anxiety**, **Bipolar**, **Depression**, and **Suicidal Messages**.

### **Models Evaluated**:

* **Bernoulli Naive Bayes**
* **Decision Tree**
* **Logistic Regression**
* **XGBoost (XGB)**

Among the models, **XGBoost** emerged as the top performer with an accuracy of **81%** and superior classification of different mental health states. The model demonstrated high F1 scores, particularly in **Normal (93%)**, **Anxiety**, and **Bipolar** (85%). The confusion matrix and word cloud analysis revealed some overlap between **depression** and **suicidal messages**, but XGBoost still provided the most accurate classification.

### **Key Features**:

* **Data Preprocessing**: Includes **tokenization**, **lemmatization**, and **TF-IDF** feature extraction.
* **Model Training**: Utilized **GridSearchCV** for hyperparameter tuning and **RandomOverSampler** for handling class imbalance.
* **Visualization**: Generates **WordClouds** and **Confusion Matrices** to analyze model performance.
* **Evaluation**: Includes **accuracy**, **precision**, **recall**, and **F1 score** metrics for each classifier.

**Technologies Used:**

* **Python**(for machine learning and data processing)
* **Google Colab** (for model training with A100 GPU)
  Scikit-learn, XGBoost, nltk, seaborn, matplotlib


