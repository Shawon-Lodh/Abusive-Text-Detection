# Abusive Text Detection : From Traditional Machine Learning to Deep Learning Approaches

Today, social media manifestations have grown so rapidly that certain extremely unacceptable social problems such as sexism, racism, and other forms of violent and cyberbullying
activity are also stimulated by provocative, abusive, or hateful words. The psychological impact on individuals of such violence can be severe and long-lasting. As a result, there had
been a substantial research effort that focused on studying these types of abusive behavior on
common social networks such as Facebook and Twitter in the field of natural language processing (NLP). Various Hate and Offensive Speech datasets on Twitter of greater scale and
reliability can now be found on various sites. In this paper, we identified an existing dataset
and examined several algorithms based on machine learning and deep learning, such as Linear Support Vector Classifier (LinearSVC), K-Nearest Neighbors (KNN), Logistic Regression
(Logit) Classifier, Multinomial Na¨ıve Bayes (MNB), Random Forest (RF), Long Short Term
Memory (LSTM) and Gated Recurrent Unit (GRU) to detect abusive Twitter content. We have
performed parameter tuning to increase the performance of the algorithms and measured recall, precision, and f1-score of different classifiers as well. We also presented the accuracy
of different classifiers using trainable models and pre-trained word embedding models such as
GloVe and FastText. Experimental results showed that GRU worked with the best performance
in the single-directional mode using the GloVe (glove-twitter-200) embedding with the highest
accuracy of 95.26%
