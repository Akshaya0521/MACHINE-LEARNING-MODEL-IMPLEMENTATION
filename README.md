# MACHINE-LEARNING-MODEL-IMPLEMENTATION
COMPANY: CODTECH IT SOLUTIONS

NAME: NIMMA AKSHAYA

INTERN ID: CT08WGN

DOMAIN: Python Programming

BATCH DURATION: February 25th, 2025 to March 25th, 2025

MENTOR NAME: NEELA SANTHOSH

**Description**
This Python code performs spam message classification using a Naive Bayes model with the following steps:

Data Loading: It loads a dataset from a URL containing SMS messages labeled as "ham" (non-spam) and "spam". The dataset is read into a Pandas DataFrame.

Data Preprocessing: The 'ham' and 'spam' labels are converted into numerical values (0 for ham, 1 for spam).

Text Vectorization: The CountVectorizer is used to convert the text data into a bag-of-words representation, removing common English stopwords.

Train-Test Split: The dataset is split into training and testing sets (80% training, 20% testing) using train_test_split.

Model Training: A Multinomial Naive Bayes model (MultinomialNB) is trained on the training data.

Predictions: The trained model is used to predict labels for the test set.

Model Evaluation: The accuracy of the model is printed, along with a detailed classification report (precision, recall, F1-score). A confusion matrix is also generated and visualized using a heatmap to show how well the model predicted 'ham' and 'spam' messages.

**Output of the Task**
