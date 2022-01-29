## Hate Speech Classification
A supervised-learning text classification project.

### Datasets

Stored in ./datasets

 - hatebase_dict - A lexicon of hateful words from: https://hatebase.org/

 - jigsaw - Toxic comments classification challenge from: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview

### Classifiers

 - Naive Bayes: https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.BernoulliNB.html#sklearn.naive_bayes.BernoulliNB
 
 - SVM: https://scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVC.html

 - Logistic Regression: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

 - Random Forest: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

 - Extra Trees: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesClassifier.html

 - Decision Tree: https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier

### Features


### Word2Vec

 - The w2v models are trained with help of the tutorial at: https://www.kaggle.com/c/word2vec-nlp-tutorial
 
 - For their size, they are not included in the repo, but the code under "./Scripts/word2vec/" is enough to reproduce them.