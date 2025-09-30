#Spam Mail Detection

This repository contains my implementation of the Spam Mail Detection Project, completed as part of my AI & ML Internship at CODEXINTERN.
The goal is to classify email messages as Spam or Ham using Natural Language Processing (NLP) and Machine Learning techniques.

Exploratory Data Analysis (EDA)

Performed detailed EDA including:

Dataset overview (head, tail, info)

Class distribution analysis (ham vs spam)

Text preprocessing:

Lowercasing

Tokenization

Stopword removal

Insights:

Spam messages often contain distinctive keywords and patterns.

Ham messages tend to be longer and more conversational.

Models Implemented

Two supervised learning models were trained, evaluated, and compared using Bag of Words (BoW) vectorization:

Model	Accuracy
Naive Bayes	~97%
Logistic Regression	~98%

Accuracy may vary slightly depending on preprocessing and dataset splits.

Evaluation

Each model was evaluated using:

Accuracy

Confusion Matrix (heatmap with Seaborn)

Classification Report (Precision, Recall, F1-score)

Visual comparisons help in identifying the strengths and weaknesses of each model in detecting spam.

Installation & Usage
1. Clone the repository and set up the environment
git clone https://github.com/varma1221/Spam-Mail-Detection.git
cd Spam-Mail-Detection

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

2. Run the main script
python spam_detection.py

Acknowledgements

Task Provider: CODEXINTERN

Dataset: Spam dataset — UCI Repository

Libraries: scikit-learn, pandas, nltk, matplotlib, seaborn

If you want, I can also add a “Project Highlights” section and a short demo image for your README so your Spam Mail Detection repo looks as polished as your Iris project.

Do you want me to do that?
