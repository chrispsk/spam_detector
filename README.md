1) I used CountVectorizer + TfidfTransformer for vectorizing the words and obtain the frequencies. See more options are commented out for testing without TfidfTransformer or with TfidfVectorizer. Best results I got via CountVectorizer + TfidfTransformer 
2) Using Pipeline + Grid Search
3) Using 4 different models: MultinomialNB, LogisticRegression, RandomForestClassifier and LinearSVC from SVM. Best results I obtained via LinearSVC.
