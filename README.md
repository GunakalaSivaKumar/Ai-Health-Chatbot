# Ai-Health-Chatbot
🩺 Healthcare Chatbot with Disease Prediction (Machine Learning)

This project is a Machine Learning–based healthcare chatbot that predicts possible diseases based on user-input symptoms. It uses a Random Forest Classifier trained on medical symptom data and enhances prediction accuracy through intelligent symptom extraction techniques.

The chatbot interacts with users through a command-line interface, collects health-related information, analyzes symptoms using NLP techniques (synonym mapping, exact matching, and fuzzy matching for typos), and provides:

Predicted disease

Confidence score (probability-based)

Disease description

Recommended precautions

Empathy-based health guidance

🚀 Key Features

ML-based disease prediction using Random Forest (300 estimators)

Natural language symptom input

Synonym handling and typo correction

Probability-based confidence scoring

Disease description and precaution suggestions

Interactive, user-friendly chatbot flow

🛠️ Tech Stack

Python

Pandas & NumPy

Scikit-learn

Regular Expressions (re)

difflib (fuzzy matching)

CSV-based medical knowledge datasets

🔍 How It Works

Loads and cleans training/testing datasets

Encodes disease labels using LabelEncoder

Trains a Random Forest model

Extracts symptoms from user input

Predicts disease with probability score

Displays relevant medical information and precautions



STRUCTURE OF THE CODE FOR EXECUTION

*Health_chatbot.py

*folder name "Data"
              |___dataset
              |___Testing
              |___Training

*folder name "MasterData"
              |___symptom_Description
              |___symptom_precaution
              |___Symptom_severity
        





