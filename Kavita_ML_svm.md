# Support Vector Machine

* Table of Contents
  * What is SVM
  * How does it works
  * Advantages of SVM
  
## What is SVM

As a Loan Manager,you want to identify a risky loan application to achieve lower default rate. This process of classifying customers into *potential* and *non-potential*
customers is known as ***Classification problem***. There are two steps in classification problem. One is ***learning step*** and second is ***prediction step***. In
**learning step** the model is developed from the training data. In **prediction step**, the model is then used to predict the response of given data.So, **SVM** is an
Classification problem which is easy to understand and interept.
**SVM** is a *supervised learning* algorithm like logistic regression, neural network. **SVM** is sometimes more powerful way of learning complex non-linear functions.
**SVM** is a discriminative classifier that is formally designed by a seperative **hyperplane**. It is a representation of examples as a points in data space such that 
the different categories is seperated by a gap as **wide** as possible.

![svm](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2019/11/svm1.png)

## How does SVM works 

The main objective of SVM is to seperate the data points in best possible way. When the segregation is done, the distance between the nearest points is known as the *margin*.
The approach is to select a *hyperplane* with the maximum possible margin between the support vectors in the given data-sets.
To select the maximum hyperplane in the given sets, the support vector machine follows the following sets:
  * Generate hyperplanes which segregates the classes in the best possible way
  * Select the right hyperplane with the maximum segregation from either nearest data points

![svm](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2019/11/svm-2.png)

## Advantages of SVM

  * Effective in high dimensional spaces
  * Still effective in cases where the number of dimensions is greater than the number of samples
  * Uses a subset of training points in the decision function that makes it memory efficient
