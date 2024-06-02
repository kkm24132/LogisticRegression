## What is LogisticRegression
This supervised learning algorithm predicts categorical response variables, such as “yes/no” answers to questions. It can be used for applications such as classifying spam and quality control on a production line.

This type of statistical model (also known as "logit model") is often used for classification and predictive analytics. Since the outcome is a probability, the dependent variable is bounded between 0 and 1. In logistic regression, a logit transformation is applied to the odds—that is, the probability of success divided by the probability of failure. This is also commonly known as the log odds, or the natural logarithm of odds, and the following formulas represent this logistic function: 

Logit(pi) = 1/(1+ exp(-pi))

ln(pi/(1-pi)) = Beta_0 + Beta_1*X_1 + … + B_k*K_k

- In this logistic regression equation, logit(pi) is the dependent or response variable and x is the independent variable.
- The beta parameter, or coefficient, in this model is commonly estimated via maximum likelihood estimation (MLE).
- This method tests different values of beta through multiple iterations to optimize for the best fit of log odds.
- All of these iterations produce the log likelihood function, and logistic regression seeks to maximize this function to find the best parameter estimate.
- Once the optimal coefficient (or coefficients if there is more than one independent variable) is found, the conditional probabilities for each observation can be calculated, logged, and summed together to yield a predicted probability.
- For binary classification, a probability less than .5 will predict 0 while a probability greater than 0 will predict 1.  After the model has been computed, it’s best practice to evaluate how well the model predicts the dependent variable, called goodness of fit. The Hosmer–Lemeshow test is a popular method to assess model fit.

## Linear Models for Classification / Logistic Regression

The following is a quick snapshot of step-wise learning path for fundamentals.

![LR Learning Steps](https://github.com/kkm24132/LogisticRegression/blob/main/Image/LR_LearningSteps.jpg)


## Recommendation
- Focus on Core Concepts
- Learn Mathematics behind algorithm(s)
- Apply using use cases and practice
- Leverage Python or R programming, and then move to cloud platforms (AWS Sagemaker or Azure ML or GCP ML or Watson or KNIME etc.)


## Approach
- Follow CRISP-DM methodology diligently
- Emphasis on EDA, Feature Engineering, Model Diagnostics and then go to Model Development, Model Evaluation
- Leverage statsmodels for statistical analysis, inferences for interpretation of coefficients, feature selections, model diagnostics etc.
- Leverage sklearn family for model solution, prediction, and further analysis of metrics for evaluation


