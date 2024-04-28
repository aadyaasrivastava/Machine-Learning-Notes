
### Define Machine Learning: 
Machine learning is a subfield of Artificial Intelligence (AI) that allows computers to learn from data without straightforward programming.  Instead of writing out every instruction, machines can improve at a specific task by analyzing data. This data can be used to predict future values, classify information, or find hidden patterns within the data.

#### Types of Machine Learning
Majorly there are two categories of machine learning: **supervised learning** and **unsupervised learning**. 
These categories are determined by the type of data and the learning objective.
* **Supervised Learning**: Supervised learning, also called supervised machine learning, is a type of machine learning and artificial intelligence. It involves using labeled data sets to train algorithms to classify data or predict outcomes accurately. This means each data point has a corresponding label or target value that the model is trying to predict. The model learns the relationship between the features (inputs) and the target variables (labels) during training. Then, it can use this learned relationship to predict the target variable for new, unseen data points. 
    * Common supervised learning tasks include classification (e.g., spam detection, image recognition) and regression (e.g., weather forecasting, stock price prediction).

* **Unsupervised Learning**: Unsupervised learning involves ML algorithms to analyze and group unlabeled data sets, finding hidden patterns without human intervention. Its capability to identify similarities and differences in data makes it useful for various tasks like data analysis, cross-selling, customer segmentation, and image recognition. The model does not have any predefined labels or target values. The goal of unsupervised learning is to find hidden patterns or structures within the data itself. These patterns can be used for tasks like anomaly detection, customer segmentation, or dimensionality reduction.
    * Common unsupervised learning tasks include clustering (e.g., grouping similar data points) and dimensionality reduction (e.g., reducing the number of features without losing important information).

--
-
### Linear Regression
Linear regression is a fundamental statistical technique used for modeling the relationship between a dependent variable (often denoted as \( y \)) and one or more independent variables (often denoted as \( x \)). It assumes a linear relationship exists between the independent variable(s) and the dependent variable. The goal of linear regression is to find the best-fitting straight line that describes this relationship between x and y.

The equation of a simple linear regression model with one independent variable can be expressed as:

\[ y = mx + c \]

Where:
- \( y \) is the dependent variable.
- \( x \) is the independent variable.
- \( m \) is the slope of the line (also known as the coefficient of the independent variable).
- \( c \) is the intercept of the line (the value of \( y \) when \( x \) is 0).

The coefficients \( m \) and \( c \) are estimated from the data to minimize the error in predicting \( y \) from \( x \).

#### Best Fit Line
The best fit line is the straight line that best represents the relationship between the independent and dependent variables. It minimizes the difference between the observed values and the values predicted by the line. In other words, it is the line that minimizes the sum of the squared differences between the actual values of the dependent variable and the values predicted by the line.

#### Types of Linear Regression
1. **Simple Linear Regression**: In simple linear regression, there is only one independent variable. The equation of the line is \( y = mx + c \), where \( m \) is the slope and \( c \) is the intercept.
2. **Multiple Linear Regression**: In multiple linear regression, there are multiple independent variables. The equation of the linear model is extended to accommodate multiple predictors:
![multiple linear regression](https://imgur.com/Vloky0u.png)

### Important Algorithms and Terminologies related to Linear Regression and Machine Learning
#### Cost or loss function
The cost or loss function, also known as the objective function, is a mathematical function that quantifies the difference between the predicted values of a model and the actual values of the target variable (dependent variable) in a dataset. It represents how well the model is performing on the given data.

In the context of linear regression, the most commonly used cost or loss function is the Mean Squared Error (MSE). The MSE measures the average squared difference between the predicted values and the actual values of the target variable.

#### Mean Squared Error
MSE stands for Mean Squared Error. It is a commonly used metric for evaluating the performance of a regression model, including linear regression.

Mathematically, Mean Squared Error (MSE) is calculated as the average of the squared differences between the actual values (observed values) and the predicted values of the dependent variable. It provides a measure of the average squared deviation of the predictions from the actual values.

#### Gradient Descent
Gradient Descent is an iterative optimization algorithm used to find the minimum of a function. In the context of linear regression, it can be used to minimize the cost function associated with the model parameters (e.g., MSE). It iteratively updates the parameters in the direction of the steepest descent of the cost function until convergence is reached.
