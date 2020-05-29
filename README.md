# Spam_Classification

## Using python to set up NLP data procee pipeline and train Predictive model to classify whether an SMS message is a spam or ham.

## Dataset is downloaded from UCI Machine Learning Repository [https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection].

## Project highligh:
1.Exploratory Data Analysis(EDA)--- Include visulization/words map/new feature creation.

2.NLP data process pipeline:Remove punctuation,tokenization, remove stopwords and vectorization by using TF-IDF.

3.Box-Cox transformation for punctuation percentage feature.

4.Fit Random Forest model and Gradient Boosting model by using Grid-search(find the best hyperparameters for models).

5.Select random forest model as the final optimization model throungh considering business need(optimize precision when deal with spam messages).

## Future Improvement:
Combine Grid-Search with K-fold cross validation. 



