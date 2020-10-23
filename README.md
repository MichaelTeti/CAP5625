# CAP5625 Coursework  
  
* [Assignment 1](https://github.com/MichaelTeti/CAP5625/blob/main/CAP5625_Assignment1_RidgeRegression.ipynb)
  - Implement ridge regression with cross validation via batch gradient descent "by hand" (i.e. without sklearn, pytorch, glmnet, etc.) in the programming language of your choice 
  - Plot coefficient values vs ridge tuning parameter lambda 
  - Plot the mean MSE across all cross validation folds for each lambda
  - Print the optimal value of lambda found with cross validation
  - Print the optimal coefficient vector
  - Compare fit against that of an ML library (e.g. sklearn, glmnet, etc.)  
* [Assignment 2](https://github.com/MichaelTeti/CAP5625/blob/main/CAP5625_Assignment2_ElasticNet_CoordinateDescent.ipynb)
  - Implement elastic net via batch coordinate descent with cross validation "by hand" in the programming language of your choice
  - Plot coefficient values vs regularization parameter lambda for each value of alpha
  - Plot the MSE across all CV folds over lambda for each alpha
  - Print optimal value of lambda and alpha found with CV
  - Print the optimal coefficient vector 
  - Compare parameters found with elastic net to those with alpha = 1 (ridge) and alpha = 0 (lasso)
