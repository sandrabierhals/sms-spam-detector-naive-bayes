# SMS Spam Detection using Naive Bayes algorithm

## Overview

This project implements a machine learning model to classify SMS messages as **spam** or **ham (not spam)** using the Multinomial Naive Bayes algorithm.

The model is trained on a dataset containing over **5,000 labeled SMS messages**, allowing it to learn patterns associated with spam and legitimate communication.

This project demonstrates the complete machine learning pipeline, including text preprocessing, feature extraction, model training, and evaluation.

It also highlights how classical probabilistic models remain effective for text classification tasks.

---

## Notes

This project was developed as part of an academic assignment and adapted for portfolio purposes.

---

## Machine Learning Approach

- Supervised Learning
- Multinomial Naive Bayes
- Laplace Smoothing
- Bag of Words (CountVectorizer)

---

## Features

- Text preprocessing (lowercasing, punctuation removal)
- Feature extraction using Bag of Words
- Model training with Multinomial Naive Bayes
- Model evaluation (accuracy, precision, recall, F1-score)
- Confusion matrix visualization
- Testing with new SMS messages

---

## Dataset

SMS Spam Collection Dataset (UCI Machine Learning Repository)

https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

---

## Results

- Accuracy: **~98.7%**
- High precision in spam detection
- Very low number of false positives
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

## Future Improvements

- Deploy the model as an API (Flask/Django)
- Support multiple languages
- Improve performance using advanced NLP techniques (TF-IDF, embeddings)
- Experiment with more complex models (e.g., neural networks)

---



