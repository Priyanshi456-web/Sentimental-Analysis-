# Sentiment Analysis Using NLP

## Overview
A Twitter hate speech classification system built using 
Natural Language Processing and Machine Learning techniques, 
achieving **94.7% accuracy** using Support Vector Machine (SVM).

## Dataset
- **Source:** Twitter Hate Speech Dataset (Kaggle)
- **Type:** Unstructured text data (tweets)
- **Labels:** Hate speech vs Normal speech

## Tech Stack
- **Language:** Python
- **Libraries:** NLTK, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

## Project Pipeline
1. **Data Collection** - Twitter hate speech dataset from Kaggle
2. **Data Preprocessing**
   - Removed noise (URLs, special characters, stopwords)
   - Tokenization (splitting text into words)
   - Stemming using NLTK
3. **Feature Extraction**
   - Count Vectorizer to convert text into numerical format
   - Visualized high frequency terms using WordCloud
4. **Model Building**
   - Logistic Regression
   - Support Vector Machine (SVM) ✅ Best Model
   - Decision Tree
5. **Evaluation**
   - Accuracy: **94.7%**
   - Metrics: Accuracy, Precision, Recall

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~89% |
| Decision Tree | ~88% |
| **SVM** | **94.7%** |

## Why SVM Performed Best?
SVM works exceptionally well on high dimensional sparse data 
like text after vectorization. It finds the optimal hyperplane 
with maximum margin between classes.

## How to Run
```bash
git clone https://github.com/Priyanshi456-web/Sentimental-Analysis-
jupyter notebook SA_using_NLP.ipynb
```

## Future Improvements
- Use TF-IDF instead of Count Vectorizer
- Try BERT or transformer based models
- Deploy as a web app using Flask or Streamlit

