# Sentiment Analysis
Sentiment analysis using TF-IDF, Naive Bayes and SVM

## Objective
The objective of this project is to classify text comments into different emotion categories using machine learning techniques.

## Dataset
The dataset contains text comments labelled with three emotions:
- Anger
- Joy
- Fear

The dataset was obtained from Kaggle and used for educational purposes.

## Technologies Used
- Python
- Pandas
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Google Colab

## Steps Performed
1. Loaded and explored the dataset.
2. Cleaned the text by converting it to lowercase and removing URLs, special characters, and extra spaces.
3. Removed English stopwords.
4. Converted the text into numerical features using TF-IDF.
5. Split the dataset into training and testing sets.
6. Trained two machine learning models:
   - Naive Bayes
   - Support Vector Machine (SVM)
7. Evaluated and compared the models using accuracy and weighted F1-score.

## Results

| Model | Accuracy | Weighted F1-score |
|---|---:|---:|
| Naive Bayes | 88.97% | 88.97% |
| Support Vector Machine (SVM) | 94.11% | 94.10% |

SVM performed better than Naive Bayes on this dataset.

## Conclusion
This project demonstrates how text preprocessing and TF-IDF feature extraction can be used for emotion classification. Among the two models, SVM achieved better performance on the test dataset.

## Tools
The assignment was developed using Google Colab and Python.

## Dataset Source
The dataset was obtained from Kaggle. Please refer to the original Kaggle dataset page for its source and licence information.
