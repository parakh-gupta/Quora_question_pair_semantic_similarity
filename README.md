# Predicting Similar Questions

The objective of this analysis is to use different Natural Language Processing methods to predict if pairs of questions have the same meaning (semantic similarity). The data is from Quora and hosted on Kaggle: https://www.kaggle.com/quora/question-pairs-dataset. There are over 400,000 lines of potential question duplicate pairs. Each line contains IDs for each question in the pair, the full text for each question, and a binary value that indicates whether the line truly contains a duplicate pair.

The sections of this analysis include:

Transforming the text
Method 1: TfidfVectorizer
Method 2: Doc2Vec
