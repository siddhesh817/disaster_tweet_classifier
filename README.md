# Disaster_Tweet_Classifier
This project is a machine learning model designed to classify tweets as either disaster-related or non-disaster content. Using natural language processing (NLP) techniques, the model processes text data to predict if a tweet pertains to an emergency or not.
Key Features
Data Acquisition: Uses a dataset containing tweet text and a binary label indicating if the tweet relates to a disaster.

Data Preprocessing:
-Text cleaning (removal of URLs, hashtags, and punctuation).
-Tokenization using NLTK.
-Removal of stopwords and stemming for improved feature extraction.

Feature Engineering:
-Utilizes TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text into numerical format.

Model Training:
-Employs multiple models such as:
-Logistic Regression
-Random Forest Classifier
-Support Vector Classifier (SVC)
-Hyperparameter tuning via GridSearchCV to optimize model performance.

Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, and Confusion Matrix are used to measure the model's performance.

Model Persistence: The trained model is serialized and saved as a .pkl file for future use.
