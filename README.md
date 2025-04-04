## <p align="center">Adult Income Dataset</p>
1. In this project, I build a Gaussian Naïve Bayes Classifier model to predict whether a person makes over 50K a year. The model yields a very good performance as indicated by the model accuracy which was found to be 0.8079639676527792.
2. The training-set accuracy score is 0.8011926394185243 while the test-set accuracy to be 0.8079639676527792. These two values are quite comparable. So, there is no sign of overfitting.
3. I have compared the model accuracy score which is 0.8079639676527792 with null accuracy score which is 0.7655850138192241. So, we can conclude that our Gaussian Naïve Bayes classifier model is doing a very good job in predicting the class labels.
4. ROC AUC of our model approaches towards 1. So, we can conclude that our classifier does a very good job in predicting whether a person makes over 50K a year.
5. Using the mean cross-validation, we can conclude that we expect the model to be around 89.16% accurate on average.
6. If we look at all the 10 scores produced by the 10-fold cross-validation, we can also conclude that there is a relatively small variance in the accuracy between folds, ranging from 89.95% ccuracy to 88.39% accuracy. So, we can conclude that the model is independent of the particular folds used for training.
7. Our original model accuracy is 0.8079639676527792, but the mean cross-validation accuracy is 0.8916274556974748. So, the 10-fold cross-validation accuracy does not result in performance improvement for this model.
