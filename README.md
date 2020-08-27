# SpamDetectionInEmails

A spam detection model is created by converting text data into vectors and deep learning model.

Published an article to detially explain how the system is built: https://lionbridge.ai/articles/using-natural-language-processing-for-spam-detection-in-emails/

The dataset used is an open-source Spambase dataset from the UCI machine learning repository, that contains 5569 emails, of which 745 are spam.

Performed text preprocessing steps which involves removing puncuations, stop words, white spaces, URLs and lowering cases. And tokenized these cleaned text and then padded the tokenised text. Created a deep learning model on these padded vectors. 

Results:

Since the percentage of spam in data is often low, measured the model’s performance by F1score.
Precision: 99.21
Recall: 91.24
F1-score: 95.06

