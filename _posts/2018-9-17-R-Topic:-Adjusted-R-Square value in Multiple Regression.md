# Predictive Analysis - Multiple Regression and using the Adjusted R-Square Value

When we want to predict the outcome of a variable based on let's say, 2 other variables, we cannot run correlation ceofficient. Because that only explains correlation between 2 variables. 

* _Multiple Regression: how 2 (or more) explanatory variables explain 1 dependent (target) variable._

When considering whether or not to use 2 or more explananatory variables as predictors, use the *adjusted* R-square value as your guide. This value tells you whether it is worth to add a new variable. 

Keep in mind that with the introduction of more variables, R-square value will increase, regardless of whether the new variables are good or not. That is to say, the regular R-square value will increase with the addition of ANY kind of new variable.

Your goal is to find the *maximum adjusted* R-Square value. (Your model should generally contain as few variables as possible.) If with the new variable, your adjusted R-square value increases then it is a valuable/good new variable. If your adjusted R-square value goes down with an additional variable, then it's not worth adding that new variable to your model. 
