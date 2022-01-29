## Hate Speech Classification
A supervised-learning text classification project.

### Datasets

The main dataset labeled_data is created by mapping the following datasets:

 - Mai ElSherief et. al.: https://github.com/mayelsherif/hate_speech_icwsm18

 - Davidson et. al.: https://github.com/t-davidson/hate-speech-and-offensive-language

 - Data for OffensEval competition: https://competitions.codalab.org/competitions/20011#learn_the_details-overview

The rest of the datasets of unlabeled data used for training of word2vec models are stored in 
./datasets.

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