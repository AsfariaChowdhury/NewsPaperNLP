# NewsPaperNLP
Classifying newspapers into different categories, following Skikit Learn tutorial: https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html

# 4 Categories
```
categories = ['alt.atheism', 'soc.religion.christian',
              'comp.graphics', 'sci.med']
```

# Multinomial Naive Bayes
Trained using tf-idf, where tf-idf was trained via count vectorizer

# Pipeline to Faciliate Compound Classification
*vectorizer => transformer => classifier*
Arguments are:
1. tf-idf
2. count vectorizer
3. Multinomial Bayes

> Accuracy = 83.5%

# Use SVM to Improve
> Accuracy = 91.0%
