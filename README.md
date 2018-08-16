# MACHINE_LEARNING_6
## Hackerearth Machine Learning Challenge #6
## Approach

### Feature Engineering
 For numerical Features ,some of the features were combined to create new feature.
 Categorical features were handeled by CatBoost Model.
 
### Model 
Trained two CatBoost model for the prediction.
First model is used to predict the target category, while Second model is built on top of the first model.
As the prediction For two categories damage_grade 1,5 were very good,second model is solely trained for improving the accuracy among the remaining three categories.
Second model is used to refine the prediction for subset of category (damage_grade 2,3,4 )

### Dataset
https://www.hackerearth.com/problem/machine-learning/predict-the-energy-used-612632a9-3f496e7f/

### Leaderboard
https://www.hackerearth.com/challenge/competitive/machine-learning-challenge-6-1/leaderboard/
