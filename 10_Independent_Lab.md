# Independent Lab: Decision Trees

In this assignment you will practice implementing decision trees in Python. You will use the data in the [`calihospital.txt` file](https://github.com/UM-BGEN632/week10labs/blob/main/data/calihospital.text) provided within the `data` folder.. 

## Context 

Recall that you belong to a team assigned to assess the condition of the healthcare system in California. You currently work in the Information Systems department for a consulting firm working with the state government agency that oversees the healthcare system in California. 

## Classification Trees and Regression Trees

In the previous weeks, your supervisor tasked you with subsetting and describing hospital data. Now, they would like you assess the data and build initial models. Specifically, they would like you to build decision trees. 

This assignment requires you to build *classification* trees and *regression* trees.

Decide on the predictor variables you use for these analyses. Have at least one categorical predictor and one numerical predictor. In total, have at least three predictors per model. Keep in mind that some of the variables are highly correlated (e.g., Operating Revenue and Net Patient Revenue) and should not be modeled together.

* Using `operating income` as a target variable, create a tree
* Using `operating revenue` as a target variable, create a tree 
* Using `TypeControl` as a target variable, create a tree
* Using `DonorType` as a target variable, create a tree

Now that you have built several different trees, you need to assess each one.

* Interpret your findings for these trees. Explain why you think the splits you received make sense.
* Which of these trees would you choose as your best model? Justify your position.
  * Note that you do not have to use an objective assessment, such as scoring predicted values, due to the small sample size.
 
**Save your notebook with code output and responses to the questions outlined above. Responses should be provided in Markdown cells. Then submit your notebook for grading.**