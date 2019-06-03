# Starbucks Promotion: A/B testing
This is an example of a common take home coding exercise/problem starbucks uses to evaluate potential applicants.  This was provided through Udacity's Data science nano degree as an exercise and practice.

## Installation

-  python version 3.6.5
-  There shouldn't be any required downloads in order to run this program

## Files

-  Starbucks.ipynb:  Workspace which detail analysis and decisions made in creating a model used to make predictions.
-  Starbucks.html:  html file of 'Starbucks.ipynb'.
-  test_results.py:  Function to test model using 'Test.csv'
-  Test.csv:  data from real world interaction to test model predictions.
-  training.csv:  data used for initial analysis and training of the model.

##  Summary

Starbucks did a test to evaluate the effect of promotions.  There were two groups, a control group who did not receive a promotion, and a treatment group who did receive a promotion.  There were 7 unnamed variables along with whether or not the individual made a purchase.  There was a very small ratio of people to purchases so when creating a model we needed to have a high recall while maintaining precision.  A linear regression was used and the threshold for sending a promotion was lowered.  To balance recall and precision the F1 score was maximized to set the threshold for sending a promotion in the model.  This result performed better than the results of the Starbucks model.

## Authors and Acknowledgement

Author: Ryan Mezera

Acknowledgement:  Data was provided from Udacity's data science nano degree program.
