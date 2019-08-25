# Prediction Intervals in Linear Regression

This post covers how to calculate prediction intervals for Linear Regression. Normally when modeling, we get a single value from a regression model. But what if that value is used to plan or make important decisions?  

Then a single value may overstate our confidence when we'd like to know our uncertainty or error margin. Sure, you can look at a general error score for all of your predictions like RMSE, but what about for a single prediction? Prediction intervals give you a range for the prediction that accounts for any threshold of modeling error that matters to you. Similar to confidence intervals you can pick a threshold like 95%, where you want the actual value to fall into a range 95% of the time. This is extremely nice when planning, as you can use the upper and lower bounds in your estimation process.  

I've created a small method (with some input from here) to predict a range for a certain confidence threshold that matters to you or your project. See the notebook to view the code and feel free to ask questions on this repo.  
