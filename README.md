# Spam Mail Detection

This repository contains my implementation of the **Spam Mail Detection Project**, completed as part of my **AI & ML Internship at CODEXINTERN**.  
The goal is to classify email messages as **Spam** or **Ham** using Natural Language Processing (NLP) and Machine Learning techniques.

---

## Exploratory Data Analysis (EDA)

Performed detailed EDA including:

- **Dataset Overview**: Used `.head()` to understand the dataset.  
- **Class Distribution**: Analyzed the count of `ham` vs `spam` messages.  
- **Text Preprocessing**:
  - Lowercasing text  
  - Tokenization  
  - Stopword removal  
- **Key Insights**:
  - Spam messages often contain distinctive keywords and patterns.
  - Ham messages tend to be longer and more conversational.

---

## Models Implemented

Two supervised learning models were trained, evaluated, and compared using **Bag of Words (BoW)** vectorization:

| Model                  | Accuracy |
|------------------------|----------|
| Naive Bayes           | ~97%     |
| Logistic Regression   | ~98%     |

> Accuracy may vary slightly depending on preprocessing and dataset splits.

---

## Evaluation

Each model was evaluated using:

- **Accuracy**
- **Confusion Matrix** (heatmap with Seaborn)
- **Classification Report** (Precision, Recall, F1-score)

Visual evaluations allow deeper insight into model performance and highlight strengths and weaknesses in spam detection.

---

## Installation & Usage

### 1. Clone the repository and set up the environment
```bash
git clone https://github.com/varma1221/Spam-Mail-Detection.git
cd Spam-Mail-Detection

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
