# Class 13 - Linear Regressions

## [How to Run Linear Regressions](https://www.activestate.com/resources/quick-reads/how-to-run-linear-regressions-in-python-scikit-learn/)

- Find the straight line that best fits the data points
- Can also use that straight line to predicts new data points
- Fundamental ML algorithm
- Scikit-learn is a python package for predictive data analysis, including linear regression, and is commonly used in ML

## [Intro to Simple Linear Regressions](https://www.youtube.com/watch?v=KsVBBJRb9TE)

- Youtube video explaining a linear regression problem
- Explanatory variable (easy to measure variable): x
- Response variable (hard to measure variable): y

## [Linear Regression in Python](https://realpython.com/linear-regression-in-python/)

- Regression searches for relationship between variables
- Another way to think about it: consider a phenomenom of interest and a number of observations. With an observation that one depends on the other, you try to establish a relationship among them

## [Train Test Split](https://builtin.com/data-science/train-test-split)

- In the supervised learning field, building a model to perform on new data is a practice to test how the model performs on it
- If new data is unavailable, then use train test split validation process
- Train test split is a model validation procedure that allows you to simulate how a model would perform on new/unseen data
    - It splits data into a training set to train the model and test set to test the model

## Additional Resources

[What is Linear Regression?](https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/what-is-linear-regression/)

### Questions

1. Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?
- Linear regression plots a "best-fit" straight line across data points. It can be used to gain insights on the relationship between an explanatory variable and response variable for data analysis and it can also be used to predict future data points for machine learning.

2. Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions.
- Steps needed to begin using Python's Scikit library:
    1. Import the packages and classes that you need.
    2. Provide data to work with, and eventually do appropriate transformations.
    3. Create a regression model and fit it with existing data.
    4. Check the results of model fitting to know whether the model is satisfactory.
    5. Apply the model for predictions.
- Functions available at: [here](https://realpython.com/linear-regression-in-python/)

3. What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?

- Train test split in a validation process to help compare how a model performs against new data. It contributes to machihne learning by training a model to identify insights and make predictions from the training set and it help evaluate the model's performance using the test set

## Things I want to know more about

- What are some examples of a data set that uses train test split and what are the takeaways from executing that validation process versus not using that process?