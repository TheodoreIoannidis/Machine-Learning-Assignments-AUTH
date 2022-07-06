# Assignment on Ensembles

We are asked to use different ensemble methods in order to find the best possible ensemble and consequently the model which is going to perform the best when used in production. We use cross validation so as to make more sound assumptions for the performance of each ensemble.

We were instructed to use the metrics balanced accuracy and  weighted f1 score.

I chose to use the Stacking Classifier with 3 complex estimators (MLP,RandomForestClassifier and SVC) and Logistic Regression as the final classifier because it outperformed all the other models that I tested. It achieved F1 Weighted-Score: 0.8657
and Balanced Accuracy: 0.8593.

See:

* https://scikit-learn.org/stable/modules/classes.html?highlight=ensemble#module-sklearn.ensemble

* https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_validate.html?highlight=cross_validate#sklearn.model_selection.cross_validate