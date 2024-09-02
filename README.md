# Spam-Ham-Classification
Overview
This project focuses on classifying SMS messages as either spam or ham (non-spam) using machine learning techniques. The goal is to develop an accurate model that can differentiate between spam and legitimate messages based on various features extracted from the text.

Dataset
Original Dataset: SMSSpamCollection.tsv - Contains SMS messages labeled as 'spam' or 'ham'.
Cleaned Dataset: SMSSpamCollection_cleaned.csv - Preprocessed version of the dataset for use in training and testing.
Features
Data Preprocessing: Text cleaning, tokenization, and feature extraction.
Model Selection: Implementation and comparison of various machine learning algorithms.
Model Performance
Best Model Accuracy: Achieved 97.5% accuracy with the optimized classification model.
Techniques Used: Data preprocessing, feature extraction, and hyperparameter tuning.
Steps to Reproduce
Clone the Repository

bash
Copy code
git clone https://github.com/Priyanshuugupta/Spam-Ham-Classification.git
Install Required Libraries

Ensure you have the following libraries installed:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
Run the Jupyter Notebook

Open the Spam-Ham Classification.ipynb notebook in Jupyter and run the cells to execute the code and view the results.

Data Files

Place the SMSSpamCollection.tsv and SMSSpamCollection_cleaned.csv files in the project directory.

Usage
Data Analysis: Explore and analyze the dataset to understand message characteristics.
Model Training: Train various machine learning models and compare their performance.
Prediction: Use the trained model to classify new SMS messages.
Conclusion
This project demonstrates the effectiveness of machine learning in text classification tasks. By applying various algorithms and optimizing parameters, a high accuracy of 97.5% was achieved, showcasing the model's reliability in distinguishing between spam and ham messages.
