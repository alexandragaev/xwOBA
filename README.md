# xwOBA

Three predictive models were leveraged to estimate wOBA on balls in play for 2022 MLB data. The first model built was k-nearest neighbors and then decision tree and random forests were the next models built. Each model was evaluated and compared to one another through calibration curves and log loss.

For the k-nearest neighbors model, the data of launch angle, exit velocity and wOBA values were visualized through a scatter plot with wOBA values on a coolwarm color scale.  Then the outcome events of out, single, double, triple, and homerun were indexed. The data was split into a test and training set, it was scaled, cross validation (GridSearchCV) was leveraged to determine the best k value, and the model was accessed through log loss and calibration curves for each event.

For the decision tree and random forest model, the data went through the same model preparation steps as the k-nearest neighbor model. Calibration curves were created for each model type with the decision tree being more calibrated than the random forest for each event. 



