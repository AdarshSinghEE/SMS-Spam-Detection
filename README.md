# SMS Spam Detection

A machine learning project to classify SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

## 📌 Project Overview
- Cleaned and explored the UCI SMS Spam Collection dataset
- Applied NLP preprocessing: lowercasing, tokenization, stopword removal, stemming
- Vectorized text using TF-IDF
- Trained and compared 12 ML classifiers
- Best model: Multinomial Naive Bayes (high precision on spam detection)

## 📁 Project Structure
sms-spam-classifier/
├── SMSSpamDetection.ipynb   # Main notebook
├── requirements.txt         # Dependencies
├── .gitignore
└── README.md
## 📦 Dataset Setup
1. Download the dataset from [Kaggle - UCI SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
2. Rename the downloaded file to `spam.csv`
3. Place it in the project root folder

## 🚀 How to Run
1. Clone the repository
```bash
   git clone https://github.com/your-username/sms-spam-classifier.git
   cd sms-spam-classifier
```
2. Install dependencies
```bash
   pip install -r requirements.txt
```
3. Add the dataset as described above
4. Open the notebook
```bash
   jupyter notebook SMSSpamDetection.ipynb
```

## 📊 Models Compared
| Model | Description |
|-------|-------------|
| Multinomial Naive Bayes | Best performer |
| Bernoulli Naive Bayes | - |
| Gaussian Naive Bayes | - |
| Logistic Regression | - |
| SVM | - |
| Decision Tree | - |
| Random Forest | - |
| KNN | - |
| AdaBoost | - |
| Bagging Classifier | - |
| Extra Trees | - |
| Gradient Boosting | - |