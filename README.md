# SMS Spam Classifier

A machine learning project that classifies SMS messages as spam or legitimate (ham) using Natural Language Processing and Logistic Regression.

## 📊 Project Overview

This project builds a spam detection system that achieves **96.41% accuracy** on the SMS Spam Collection dataset. The classifier uses TF-IDF vectorization to convert text into numerical features and Logistic Regression for classification.

## 🎯 Features

- Text preprocessing and vectorization using TF-IDF
- Machine learning classification with Logistic Regression
- Model persistence (save/load functionality)

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **scikit-learn** - Machine learning algorithms and tools

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed, then install the required libraries:
```bash
pip install pandas scikit-learn jupyter notebook
```

### Installation

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/spam-classifier.git
cd spam-classifier
```

2. This project is using with the data set from Kaggle--[Kaggle SMS Spam Collection](https://www.kaggle.com/code/ishansoni/sms-spam-collection-dataset/notebook). Download the file and place `spam.csv` in the project folder if the downloaded file is named differently. 

3. Open the Jupyter notebook:
```bash
jupyter notebook spam_classifier.ipynb
```
## 💻 Usage

### Training the Model

Run all cells in the Jupyter notebook sequentially. The notebook will:
1. Load and preprocess the data
2. Split data into training and testing sets
3. Vectorize text using TF-IDF
4. Train a Logistic Regression model
5. Evaluate performance

## 📈 Model Performance

- **Accuracy**: 96.41%
- **Algorithm**: Logistic Regression
- **Vectorization**: TF-IDF (3000 features, English stop words removed)
- **Training/Test Split**: 80/20 (test_size to 0.2)

## 🧠 What I Learned

- Text preprocessing and feature extraction using TF-IDF
- Train/test split methodology and importance of testing on unseen data
- Model evaluation metrics (accuracy)
