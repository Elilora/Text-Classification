# Spam-Text-Classification

This project aims to classify text messages as spam or ham (non-spam) using machine learning models (Naive Bayes, Random Forest, Decision Tree, K Nearest Neighbor) and Natural language techniques.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Word Cloud for Spam and Ham Messages](#word-cloud-for-spam-and-ham-messages)
- [Data Transformation](#data-transformation)
- [Results](#results)
  - [Naive Bayes Classifier](#naive-bayes-classifier)
  - [K-Nearest Neighbors Classifier](#k-nearest-neighbors-classifier)
  - [Decision Tree Classifier](#decision-tree-classifier)
  - [Random Forest Classifier](#random-forest-classifier)
- [Contributing](#contributing)
- [License](#license

## **Installation**

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Elilora/spam-text-classification.git
    cd spam-text-classification
    ```

2. **Install the required libraries:**

    ```bash
    pip install numpy pandas seaborn matplotlib scikit-learn xgboost shap
    ```
    
## DATASET
The dataset used is gotten from Kaggle  https://www.kaggle.com/team-ai/spam-text-message-classification with 5157 unique values

## Data Preprocessing
Data preprocessing steps include calculating the length of messages, exploring basic statistics, and visualizing the distribution of message categories.

## Word Cloud for Spam and Ham Messages
Word clouds are generated to visualize the most common words in spam and ham messages.

## Data Transformation

Text data is preprocessed by removing special characters, converting text to lowercase, tokenizing, stemming, removing stopwords, and expanding contractions.

## **Model Building**

The following models were used to predict stroke occurrence:

- Naive Bayes Classifier
- K-Nearest Neighbors Classifier
- Decision Tree Classifier
- Random Forest Classifier

### **Steps**

1. **Split the data into training and testing sets (70% train, 30% test).**
2. **Train the models on the training set.**
3. **Evaluate the models on the testing set using accuracy and F1-score metrics.**
4. **Generate classification reports and confusion matrices.**
   
## **Results**
Various machine learning models are trained and evaluated using the processed data.

### Naive Bayes Classifier
The Multinomial Naive Bayes classifier is trained and evaluated for text classification.
- **Accuracy:** 91.06%
- **F1-score:** 10.46%
- **Detailed classification report and confusion matrix are generated in the script output.**

### K-Nearest Neighbors Classifier
The K-Nearest Neighbors classifier with `n_neighbors=2` is trained and evaluated for text classification.
- **Accuracy:** 91.06%
- **F1-score:** 10.46%
- **Detailed classification report and confusion matrix are generated in the script output.**

### Decision Tree Classifier
The Decision Tree classifier is trained and evaluated for text classification.
- **Accuracy:** 91.06%
- **F1-score:** 10.46%
- **Detailed classification report and confusion matrix are generated in the script output.**

### Random Forest Classifier
The Random Forest classifier is trained and evaluated for text classification.
- **Accuracy:** 91.06%
- **F1-score:** 10.46%
- **Detailed classification report and confusion matrix are generated in the script output.**

## **Contributing**

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## **License**

This project is licensed under the MIT License - see the LICENSE file for details.


