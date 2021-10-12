# Random-Forests in Regression
~~~ python
from sklearn.ensemble import RandomForestRegressor

# Define the model. Set random_state to i
rf_model = RandomForestRegressor(random_state = i)

# fit your model
rf_model.fit(train_X, train_y)

# Calculate the mean absolute error of your Random Forest model on the validation data
predicted = rf_model.predict(val_X)
rf_val_mae = mean_absolute_error(val_y, predicted)

print("Validation MAE for Random Forest Model: {}".format(rf_val_mae))
~~~
