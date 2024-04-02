# SC1015
SC1015 Data Science &amp; Artificial Intelligence project
#Twitter Hate Speech Detector

## Overview

In today's digital age, social media platforms like Twitter have become breeding grounds for hate speech and cyberbullying. This project aims to address this issue by developing a hate speech detector specifically tailored for Twitter. By leveraging machine learning techniques, we aim to automatically identify and flag tweets containing hateful or abusive language. Five different models - Random Forest, Nearest Neighbour, Decision Tree, Logistic Regression, and Naive Bayes - will be explored and compared to determine the most effective approach for hate speech detection on Twitter.

## Dataset

The dataset used for this project is a curated collection of data from various social media platforms including Twitter, Kaggle, Wikipedia Talk pages, and YouTube. Each instance in the dataset consists of a tweet along with corresponding annotations indicating whether it contains hate speech or not. The data encompasses different types of cyberbullying such as hate speech, aggression, insults, and toxicity. To ensure robustness and generalization, the dataset is divided into training and testing sets for model training and evaluation.

## Models

### Random Forest:
Random Forest is an ensemble learning method that constructs a multitude of decision trees during training and outputs the mode of the classes as the prediction of individual trees.
### Nearest Neighbour:
Nearest Neighbour is a simple classification algorithm that assigns the label of the majority class among its k nearest neighbors.
### Decision Tree:
Decision Tree is a flowchart-like tree structure where an internal node represents a feature, the branch represents a decision rule, and each leaf node represents the outcome.
### Logistic Regression:
Logistic Regression is a linear model used for binary classification that predicts the probability of occurrence of an event by fitting data to a logistic curve.
### Naive Bayes:
Naive Bayes is a probabilistic classifier based on Bayes' theorem with the assumption of independence between features.
## Training and Evaluation

Each model will be trained on the training dataset and evaluated on the testing dataset using various evaluation metrics such as accuracy, precision, recall, and F1-score. These metrics will provide insights into the performance of each model in identifying hate speech on Twitter. The model exhibiting the highest performance across these metrics will be selected as the best approach for hate speech detection.

## Results

The evaluation results will be presented, showcasing the performance metrics of each model and comparing their effectiveness in hate speech detection. Additionally, insights gained from the analysis will be discussed, highlighting the strengths and weaknesses of each model.

## Conclusion

Based on the evaluation results, the most effective model for hate speech detection on Twitter will be identified. Recommendations for further improvements, model optimization, and deployment of the hate speech detector will also be discussed, aiming to contribute to the ongoing efforts in combating online hate speech and fostering a safer online environment.

