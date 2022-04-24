# Pima Indians Diabetes

## 1. Dataset

[Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## 2. Metrics

### 1) Accuracy

Accuracy is the ratio of number of correct predictions to the total number of input samples.

It works well only if there are equal number of samples belonging to each class. (Balanced Dataset)

![Screen Shot 2022-04-24 at 2.07.35 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.07.35_PM.png)

For binary classification, accuracy can be calculated in terms of positives and negatives as follows:

![Screen Shot 2022-04-24 at 2.09.45 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.09.45_PM.png)

### 2) Confusion Matrix

Confusion Matrix gives us a matrix as output and describes the complete performance of the model.

There are 4 important terms :

- **True Positives** : The cases in which we predicted YES and the actual output was also YES.
- **True Negatives** : The cases in which we predicted NO and the actual output was NO.
- **False Positives** : The cases in which we predicted YES and the actual output was NO.
- **False Negatives** : The cases in which we predicted NO and the actual output was YES.

![Screen Shot 2022-04-24 at 2.20.08 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.20.08_PM.png)

### 3) Precision & Recall

• **Precision :** It is the number of correct positive results divided by the number of positive results predicted by the classifier.

![Screen Shot 2022-04-24 at 2.27.41 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.27.41_PM.png)

• **Recall :** It is the number of correct positive results divided by the number of ***all*** relevant samples (all samples that should have been identified as positive).

![Screen Shot 2022-04-24 at 2.27.58 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.27.58_PM.png)

### 4) ROC curve and AUC (Area Under Curve)

- Area Under Curve(AUC) is one of the most widely used metrics for evaluation.
- ROC curve is drawn with TPR(True Positive Rate) and FPR(False Positive Rate).

• **True Positive Rate (Sensitivity)** : True Positive Rate is defined as *TP/ (FN+TP)*. True Positive Rate corresponds to the proportion of positive data points that are correctly considered as positive, with respect to all positive data points.

![Screen Shot 2022-04-24 at 2.33.08 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.33.08_PM.png)

• **False Positive Rate** : False Positive Rate is defined as *FP / (FP+TN)*. False Positive Rate corresponds to the proportion of negative data points that are mistakenly considered as positive, with respect to all negative data points.

![Screen Shot 2022-04-24 at 2.33.14 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.33.14_PM.png)

![Screen Shot 2022-04-24 at 2.35.07 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.35.07_PM.png)

As evident, AUC has a range of [0, 1]. The greater the value, the better is the performance of our model.

### 5) Precision Recall Curve

Precision-Recall is a useful measure of success of prediction when the classes are very imbalanced.

The precision-recall curve shows the tradeoff between precision and recall for different threshold.

![Screen Shot 2022-04-24 at 2.37.39 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.37.39_PM.png)

### 6) F-1 Score

F1 Score is the Harmonic Mean between precision and recall. 

It tells you how precise your classifier is (how many instances it classifies correctly), as well as how robust it is (it does not miss a significant number of instances).

![Screen Shot 2022-04-24 at 2.40.04 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_2.40.04_PM.png)

## 3. Model evaluation with different metrics

![Screen Shot 2022-04-24 at 4.16.31 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_4.16.31_PM.png)

![Screen Shot 2022-04-24 at 4.16.41 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_4.16.41_PM.png)

## 4. Tuning the model with different thresholds

![Screen Shot 2022-04-24 at 4.18.10 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_4.18.10_PM.png)

## 5. Final Model

![Screen Shot 2022-04-24 at 4.18.51 PM.png](Pima%20Indians%20Diabetes%208bb5783b90e84f368ba301c5550f6649/Screen_Shot_2022-04-24_at_4.18.51_PM.png)