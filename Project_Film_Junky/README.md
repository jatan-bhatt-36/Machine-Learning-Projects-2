# Machine Learning for Texts

## Project Description:
The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. 
The goal is to train a model to automatically detect negative reviews. You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. 
It will need to reach an F1 score of at least 0.85.

## Instructions:
1. Load the data.
2. Preprocess the data, if required.
3. Conduct an EDA and make your conclusion on the class imbalance.
4. Preprocess the data for modeling.
5. Train at least three different models for the given train dataset.
6. Test the models for the given test dataset.
7. Compose a few of your own reviews and classify them with all the models.
8. Check for differences between the testing results of models in the above two points. Try to explain them.
9. Present your findings.


## Key Concepts:
🗝️ Data Visualization & Kernel Density Estimation (KDE) plots

🗝️ Large Language Models, Normalization, Vectorization, Lemmatization and Tokenization

🗝️ Natural Language Tool Kit (NLTK), TF-IDF, spaCy, BERT


## What I Learned:
✔️ evaluate_model() - a routine to evaluate a classification model which conforms to the scikit-learn predict interface

✔️ Without normalization, punctuation and digits can create useless tokens like '12' or '!!'.

✔️ Normaalization can decrease dimensionality and increase the model's generalization ability.

✔️ Lemmatization reduces the number of words a model needs to be trained (Eating and Ate turn to Eat).

✔️ Vectorization lets the model assign importance to words such as great and greater.
