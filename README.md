# RedWineAlcoholLevels

The purpose of my research paper was to use pycaret and its regression library to predict the alcohol levels in red wine. It uses the UCI wine data set and then pycaret runs a training set through all of its available regression algorithms. I set the data to look for an algorithm that produced the best RMSE score. Leaving 3 regression algorithms, CatBoost, Light Gradient Boost Machine and Extreme Gradient Boosting. I then ran these three algorithms through the training set and finalized them with a test set to determine which of the three algorithms was the best fit for the job. I further investigated the Catboost model by attempting to remove columns that might have been uneeded as they were lower on the feature importane plot in the evaluation but they tended to reduce the precision instead of improving the precision like I thought.

Here is the Link to my brief summary of my paper: https://youtu.be/RQwWQ_g4KQs
