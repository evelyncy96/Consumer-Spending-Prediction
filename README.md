# Consumer-Spending-Prediction

- **Goal:** Predict the amount of purchase for consumers
- **Data source:** please refer to the dataset in the repository
- **Model:** Ensemble Model(Stacking)/ Deep Neural Network/ Support Vector Regressor/ ElasticNet/ Regression Tree/ KNN Regressor

In this project, I first created a function called 'gridsearch'. In this function, I compiled the feature scaling and gridsearch into pipeline, and the return of the function including the best gridsearch score, best parameter of the model, and the MSE of test set of each model. **The model I use includes Ensemble Stacking/ Deep Neural Network/ Support Vector Regressor/ ElasticNet/ Regression Tree/ KNN Regressor.** The result shows that **Deep Neural Network is the best model** with the lowset MSE score.
