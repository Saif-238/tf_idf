This report is based on sentiement analysis , sentiement analysis is 
 technique  in Natural language process(Nlp) to classify the review(opinion) to positive or negative sentiment  .
sentiment analyze has become common technique for extracting meaningful information from human language . 
using the Term frequency – Inverse Document Frequency (TF-IDf) algorithm .

The dataset that we have is IMDB Movie Reviews it’s a csv file balanced data consists from 50,000 Movie Review 25,000 positive review and 25,000 negative review each review is an unstructured data that contain symbols html tags and numeric we split the data set 
Train dataset =.8 and test set=.2 which is 40,000 sample for training and 10,000 for testing 
The project work flow is text preprocessing,N-grams feature, classification 
Text preprocessing convert to lower case, removing extra spaces and non -letter symbols and apply steaming .
N-grams 
The preprocessed corpus is vectorized using TF-IDF with vocabulary cap 5,000 of features.
capture both single words and short phrases. This helps with expressions like “not good” and “very enjoyable.
Classification 
The classifier used is Logistic Regression from scikit-learn . Logistic Regression Ml classification models is a strong and interpretable baseline for text classification. It models the log-odds of the positive class as a linear combination of TF-IDF features, and the learned weights directly indicate which words are most associated with positive or negative sentiment  
