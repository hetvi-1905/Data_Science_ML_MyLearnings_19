# Data_Science_Machine_Learning
## All practice codes 
1) Python
2) Numpy
3) Pandas
4) Matplotlib
5) Seaborn
6) Exploratory Data Analysis
7) All basic ML Algorithms code using Libraries
8) Feature Engineering
9) Feature Selection
10) Feature Tranformation 



💁‍♀️ For more information :

📜 Important Articles to Revise all the algorithms :

****Understnading ML ALgos Theoritically:****

https://towardsdatascience.com/11-most-common-machine-learning-algorithms-explained-in-a-nutshell-cc6e98df93be

****Understnading ML ALgos Mathematically:****

https://towardsdatascience.com/the-math-behind-machine-learning-algorithms-9c5e4c87fff

🎥 Reference for visualization and Intuition of ML Algos:

📌 Supervised Algorithms

****Regression****

- Linear 
https://youtu.be/fnwlz5ARpjo

- Ridge (L2) and Lasso (L1)  (refer theory below)
https://youtu.be/Xm2C_gTAl8c

- SVR 
https://youtu.be/Fv7C46NiQiw

- KNN regressor
https://youtu.be/BvQVovMefsM

- Decision Tree Regressor
https://youtu.be/UhY5vPfQIrA

- Random Forest Regressor (Ensemble Bagging Technique)
https://youtu.be/BGiJqA-cGgQ

- Adaboost Regressor (XGboost in much much faster than Adaboost and gives almost same or more accuracy)
https://www.kaggle.com/general/218408

- Gradientboost Regressor
https://youtu.be/TyvYZ26alZs

- XGboost Regressor  
https://towardsdatascience.com/a-brief-introduction-to-xgboost-3eaee2e3e5d6#:~:text=XGBoost%20vs%20Gradient%20Boosting,can%20be%20parallelized%20across%20clusters.

****Classification****

- Logistic 
https://youtu.be/slBI5YuVUTM

- Naive Bayes 
https://in.coursera.org/lecture/machine-learning-under-the-hood/naive-bayes-ui7OL?utm_source=link&utm_medium=page_share&utm_content=vlp&utm_campaign=top_button

- SVM 
https://youtu.be/N1vOgolbjSc

- KNN Classifier
https://youtu.be/UqYde-LULfs

- Decision Tree Classifier
https://youtu.be/tNa99PG8hR8

- Random Forest Classifier (Ensemble Bagging Technique)
https://youtu.be/BGiJqA-cGgQ

- Adaboost Classifer (XGboost in much much faster than Adaboost and gives almost same or more accuracy)
https://www.kaggle.com/general/218408 

- Gradientboost Classifier
https://youtu.be/TyvYZ26alZs

- XGboost Classifier
https://towardsdatascience.com/a-brief-introduction-to-xgboost-3eaee2e3e5d6#:~:text=XGBoost%20vs%20Gradient%20Boosting,can%20be%20parallelized%20across%20clusters.

📌 UnSupervised Algorithms 

- K Means
https://youtu.be/R2e3Ls9H_fc

- DBSCAN
https://youtu.be/_A9Tq6mGtLI

- Hierarchical clustering
https://youtu.be/ijUMKMC4f9I

- PCA
https://youtu.be/47U0NCeqwQ4

📌Important theory :

Why use Ridge & Lasso?
When we create our linear model with the best-fitted line and come on testing phase then because of increased variation, our model is over-fitted, So It will not work well in the future also not provide appropriate accuracy. Therefore, to reduce overfitting, ridge and lasso regression came into the picture.

When to use which?
Lasso tends to do well if there are a small number of significant parameters and the others are close to zero (ergo: when only a few predictors actually influence the response). Ridge works well if there are many large parameters of about the same value (ergo: when most predictors impact the response).

One obvious advantage of lasso regression over ridge regression, is that it produces simpler and more interpretable models that incorporate only a reduced set of the predictors.
