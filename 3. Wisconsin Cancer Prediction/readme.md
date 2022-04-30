# Wisconsin Breast Cancer Prediction

## 1. Overview of XGBoost (eXtra Gradient Boosting)

XGBoost builds upon: 

supervised machine learning, decision trees, **ensemble learning**, and gradient boosting.

![Screen Shot 2022-04-28 at 11.29.57 AM.png](Wisconsin%20Breast%20Cancer%20Prediction%2092300e05019a4bcd8f1417d09bc5f0f1/Screen_Shot_2022-04-28_at_11.29.57_AM.png)

The term “gradient boosting” comes from the idea of “boosting” or improving a single weak model by **combining it with a number of other weak models** in order to generate a collectively strong model.

Gradient Boosting Decision Trees(GBDT) iteratively train an ensemble of shallow decision trees, with each iteration using the error residuals of the previous model to fit the next model. The final prediction is a weighted sum of all of the tree predictions.

## 2. Prediction result using XGBoost

![Screen Shot 2022-04-28 at 5.17.52 PM.png](Wisconsin%20Breast%20Cancer%20Prediction%2092300e05019a4bcd8f1417d09bc5f0f1/Screen_Shot_2022-04-28_at_5.17.52_PM.png)

![Plot of feature importances](Wisconsin%20Breast%20Cancer%20Prediction%2092300e05019a4bcd8f1417d09bc5f0f1/Screen_Shot_2022-04-28_at_5.18.24_PM.png)

Plot of feature importances

## 3. Overview of LightGBM

LightGBM is a gradient boosting framework based on decision trees to increases the efficiency of the model and reduces memory usage.

LightGBM splits the tree leaf-wise as opposed to other boosting algorithms that grow tree level-wise.

![Screen Shot 2022-04-30 at 1.35.21 PM.png](Wisconsin%20Breast%20Cancer%20Prediction%2092300e05019a4bcd8f1417d09bc5f0f1/Screen_Shot_2022-04-30_at_1.35.21_PM.png)

## 4. Prediction result using LightGBM

![Screen Shot 2022-04-30 at 1.36.16 PM.png](Wisconsin%20Breast%20Cancer%20Prediction%2092300e05019a4bcd8f1417d09bc5f0f1/Screen_Shot_2022-04-30_at_1.36.16_PM.png)

![Screen Shot 2022-04-30 at 1.36.34 PM.png](Wisconsin%20Breast%20Cancer%20Prediction%2092300e05019a4bcd8f1417d09bc5f0f1/Screen_Shot_2022-04-30_at_1.36.34_PM.png)