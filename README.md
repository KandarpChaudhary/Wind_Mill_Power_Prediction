# Wind_Mill_Power_Prediction

### Problem Statement:

> <div style="text-align: justify">It is the year 2022 and we are at the verge of a massive climatic change. With global warming at its peak and fossil fuels inching towards its extinction, it is the need of the hour to step up and take responsibility for our planet. Developing countries all over the world are making a shift towards a cleaner energy source and are looking at ways to expand their global energy source power.</div>
> <div style="text-align: justify">Switching to renewable energy sources is a great way to reduce dependency on imported fuels and increase cost efficiency. It is time we move towards a low-carbon future by embracing solar, hydro, geothermal energy and so on, to protect mother nature.</div>
> <div style="text-align: justify">An efficient energy source that has been gaining popularity around the world is wind turbines. Wind turbines generate power by capturing the kinetic energy of the wind. Factors such as temperature, wind direction, turbine status, weather, blade length, and so on influence the amount of power generated.</div>

https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-windmill-power/

### Objective:

> <div style="text-align: justify">The objective is to build a sophisticated Machine Learning model that predicts the power that is generated (in KW/h) based on the various features provided in the dataset. To analyze and implement multiple algorithms and determine which is more appropriate for a problem To get hands-on experience in Machine Learning problems.</div>

### Problem solving approach:

0. <div style="text-align: justify">Splitting the data into train and test in 80:20 ratio. (Ratio can be modified based on rows of the dataset.)</div>

> - Every step from 1 to 5 needs to be performed without expoure to test data.
1. <div style="text-align: justify">Questioning the data - Understanding the variables very carefully and formulating questions/hypothesis. (Note : These are just initial hypothesis which may or may not seem to be true after the EDA step.)</div>
2. <div style="text-align: justify">EDA - Exploring the dataset very carefully by doing univariate analysis and bivariate analysis by choosing appropriate graphs, charts and descriptive measures. Reporting the surprising elements (i.e. the one which were believed would be true in step 1 did not turn out to be true, or a result that was beyond expectation, etc.)</div>
4. <div style="text-align: justify">Missing value imputation using various methods such as mean,median or KNN imputation </div>
5. <div style="text-align: justify">Feature engineering - Suggesting some possible feature transformations (like log(X), sqrt(X), X^2, X1*X2, etc.) with reasons. Feature engineering. Suggesting some new feature generation techniques (e.g.: creating dummy variables, or using one-hot encoding, or transforming an existing feature to a new feature).</div>
6. <div style="text-align: justify">Model fitting step - Fitting various regression models by considering different sets of predictors on the training dataset. Argue the reasons for considering those predictor sets. Reporting k-fold cross-validation MAE, RMSE, R-squared and adjusted R-squared values. Choosing best model using hyperparameter tuning.</div>
7. <div style="text-align: justify">Model testing - Consider the best competing models from each algorithm and test their performances on the test data. Report the results.</div>
