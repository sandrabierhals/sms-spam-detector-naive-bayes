# SMS Spam Detection using Naive Bayes algorithm

This project implements a machine learning model to classify SMS messages as **spam** or **ham (not spam)** using the Multinomial Naive Bayes algorithm.

---

## Notes

This project was developed as part of an academic assignment and adapted for portfolio purposes.

---

## Overview

The system applies Natural Language Processing (NLP) techniques to preprocess text data and convert it into numerical features using a Bag-of-Words approach.

The model is trained using labeled SMS data and evaluated on unseen messages.

---

## Machine Learning Approach

- Supervised Learning
- Multinomial Naive Bayes
- Laplace Smoothing
- Bag of Words (CountVectorizer)

---

## Features

- Text preprocessing (lowercasing, punctuation removal)
- Feature extraction (CountVectorizer)
- Model training and evaluation
- Confusion matrix visualization
- Testing with new SMS messages

---

## Dataset

SMS Spam Collection Dataset (UCI Machine Learning Repository)

https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

---

## Results

- Accuracy: ~98%
- High precision in spam detection
- Good generalization on new messages

---

## Example

Input: Congratulations! You won a free ticket

Output: Spam


---

## Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## AI Perspective

This system can be interpreted as an intelligent agent:

- **Perception:** receiving SMS messages
- **Processing:** applying Naive Bayes classification
- **Action:** labeling as spam or ham

---



