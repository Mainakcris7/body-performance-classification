
# Classification based on Body Performance

Classifying humans based on their fitness level and body performance. `A` class refers to the best body performance. This is a practice project based on `Classification` in `Machine Learning`.
Dataset is available on `Kaggle`.




## 🚀 About Me
I'm still a Student, pursuing my B.Tech (3rd year, at 2023). I dreamt to be a Data Scientist or Data Analyst one day.



## Python Libraries used

- pandas
- numpy
- sklearn
- XGBoost
- CatBoost
- matplotlib
- seaborn


## Authors

- [@Mainakcris7](https://github.com/Mainakcris7)


## Link for the dataset

[Kaggle](https://www.kaggle.com/datasets/kukuroo3/body-performance-data)


## FAQ

#### Why you haven't used SVM?

Support Vector Machines are good for smaller dataset due to heavy calculations. I avoided using it because the dataset is quite large (shape : (13392,12)).

#### Why you haven't used Hyperparameter Tuning?

I tried to use GridSearchCV and RandomizedSeachCV both. But due to large dataset and complex models(other than the Logistic Regression), it takes so much time (GridSearchCV). RandomizedSearchCV is not a better option as it chhoses the parameters randomly, which can produce worse result (in my case, it actuall occurs).

#### Which models are you using in this project?
Logistic Regression, XGBoost, CatBoost, GradientBoosting Classifier and RandomForest.
