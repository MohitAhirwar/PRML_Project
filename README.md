# Twitter Sentiment Analysis
![image](https://user-images.githubusercontent.com/66860602/118408235-501d8080-b6a2-11eb-844a-ab9c9071eceb.png)

# Requirements :- 
There are some general library requirements for the project and some which are specific to
individual methods. The general requirements are as follows.
● Numpy, Pandas

● scikit-learn

● scipy

● nltk

The library requirements specific to some methods are:

● Multinomial Naive Bayes

● SVM

● Logistic Regression

● xgboost for XGBoost

● Linear SVC

● .Random Forest

# STRUCTURE OF CODE

Importing Important Libraries

● pandas,numpy,nltk,re,future,matplotlib.pyplot

● train_test_split,GridSearchCV

● CountVectorizer, TfidfVectorizer

● TfidfTransformer

● BernoulliNB, MultinomialNB

● metrics,roc_auc_score

● accuracy_score,label_binarize,LogisticRegression

● Pipeline,svm,LinearSVC,SVR

● RandomForestClassifier,DecisionTreeClassifier

● BeautifulSoup,stopwords,SnowballStemmer

# Reading CSV file

● Mounting from google drive or any local path
● Using pd.read_csv and encoding latin

# Preprocessing

● Lowercasing the letter

● Removing Usernames

● Removing URLs

● Removing all digits

● Removing Quotations

● Replacing Emojis with their corresponding sentiment part eg : positive emoji or negative emojis

● Replacing contractions

● Removing punctuations

● Replacing double spaces with single spaces

● Showing Plots

● Showing Word clouds

● Used Count Vectorizer

# Classifiers Used :

● Used Multinomial Naive Bayes

● Used Linear SVC

● Used Logistic Regression

● Used SVM

● Using Decision Trees

● Using Xgb

One has to simply open the colab file and keep on running all the codes.Give path for
reading the csv file.The first 3 classifiers are showing the best results

# Performance Measurements :

1. Logistic Regression

![image](https://user-images.githubusercontent.com/66860602/118408673-367d3880-b6a4-11eb-81e2-72cb05e79a24.png)

2. Multinomial Naive Bayes

![image](https://user-images.githubusercontent.com/66860602/118408684-439a2780-b6a4-11eb-8b2f-ab88c41af2b5.png)

3. Linear SVC

![image](https://user-images.githubusercontent.com/66860602/118408705-51e84380-b6a4-11eb-92c1-b2dec3f2338d.png)

# Accuracy Comparison :

Below is the results of the accuracy results of all the three classifiers used above to predict the model.

![image](https://user-images.githubusercontent.com/66860602/118408751-7fcd8800-b6a4-11eb-9055-739d9f9f098c.png)

We see that Logistic Regression has performed better as compared to the other 2.Linear SVC and
Multinomial had almost done equally better.
