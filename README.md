# Semi-Supervised Logistic Regression

This project is a demonstration of semi-supervised logistic regression using Python. In semi-supervised learning, we have access to both labeled and unlabeled data to train our model. The labeled data is used to train the initial model, and the model's predictions on the unlabeled data are used to create pseudo-labels, which are then used to further train the model.

The project is divided into three parts:

## Part A: Logistic Regression
In this part, we define the sigmoid function and visualize it using the matplotlib library. We then load a dataset using pandas and split it into training, testing, and unlabeled datasets. We also check the dimensions of the data.

## Part B: Evaluating Classifier
In this part, we fit the logistic regression model on the labeled dataset and evaluate its accuracy and f1 score on the training and testing data. We also plot a confusion matrix to visualize the results.

## Part C: Self-Training
In this part, we implement self-training using logistic regression. We first fit the logistic regression model on the labeled dataset, and then we use it to generate pseudo-labels for the unlabeled data. We use the pseudo-labeled data to retrain the model and evaluate its performance. We repeat this process until there are no more high-probability pseudo-labels.

The code is well-documented, with comments explaining each step. It uses the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn

The project provides a basic implementation of semi-supervised logistic regression and can be further developed to accommodate larger datasets or more complex models.
