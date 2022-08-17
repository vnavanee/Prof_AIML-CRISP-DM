This data comes from Kaggle dataset and has approximately 426k rows. This used cars dataset with features such as condition of the vehicle, odomter reading, year, make and model of the vehicle and other salient features of a used car.

Used CRISP-DM framework to organize the project and run models.

Data was  improved with car model names cleanup. To run the models the top 259 car models by number of units sold was used.

With the linear regression model the mean squared error for test data was better than the training error. While this model is based on data trimmed based on the top 259 car models, the model could be trained better with grouping similar car models. The model that performed wellwas the model with Ridge Regression and alpha of 1000.0 and Sequential Feature Selection number of features to select =2. This model will perform well as long as the training model is fed a car model that it has seen during training. Moreover, one could tell looking at the data cursorily that certain models have sold more than others and possibly hold that trend in the future.

Merging similar data and running the model again and also making sure the test and train split produces similar distribution of data will ensure a robust model. 
