# How-to-Talk-scikit-learn-Machine-Learning-Library

January 15, 2021

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me! 😊

We've had an incredible mathematical tour of machine learning. We learned about data, and how to derive parameters representing out data by loss functions or least square regression. We rewrote the summation loss function into matrix vector format as in: Wtranspose dot product X. W is the coefficient matrix while the X is feature vector. When there multiple dimensions for feature we created covariance, correlation matrices. We analyze correlation between features, rank them, select and extract.

We talked about optimizing loss functions and the many tools at our disposal.

Now we venture forward with scikit-learn. Now thanks to an active Python community of developers, we don't have to rewrite data science from 
scratch. From simple code snippets , we can leveraged the use of optimized algorithms written in Fortran and C.

What we'll do is take a look at the scikit-learn API, which, as mentioned, combines a user-friendly and consistent interface with a highly 
optimized implementation of several classification algorithms. The scikit-learn library offers not only a large variety of learning algorithms,
but also many convenient functions to preprocess data and to fine-tune and evaluate our models.

After standardizing the training data, we can now train a perceptron model using the code snippet below:

from sklearn.linear_model import Perceptron

ppn = Perceptron(eta0=0.1, random_state=1)

ppn.fit(X_train_std, y_train)

...

After loading the Perceptron class from the linear_model module, we initialized a new Perceptron object and trained the model via the fit method.
Here, the model parameter, eta0, is equivalent to the learning rate, eta, that we used in our own perceptron implementation, and the n_iter parameter
defines the number of epochs (passes over the training dataset). 

I included some jupyter notebooks to serve as study guide and practice.

I included some posts for reference.

https://github.com/noey2020/How-to-Talk-Linear-Regression-Optimizing-Loss-Function-Mean-Squared-Error

https://github.com/noey2020/How-to-Talk-an-Introduction-to-Linear-Regression

https://github.com/noey2020/Hpw-to-Talk-More-Generative-Models

https://github.com/noey2020/How-to-Talk-Gaussian-Generative-Models

https://github.com/noey2020/How-to-Talk-Multivariate-Gaussian

https://github.com/noey2020/How-to-Talk-Linear-Algebra-Review-3

https://github.com/noey2020/How-to-Talk-Linear-Algebra-Review-2

https://github.com/noey2020/How-to-Talk-Linear-Algebra-Review-1

https://github.com/noey2020/How-to-Talk-2D-Generative-Modeling

https://github.com/noey2020/How-to-Talk-Probability-Review-3

https://github.com/noey2020/How-to-Talk-Probability-Review-2

https://github.com/noey2020/How-to-Talk-Generative-Modeling-in-One-Dimension

https://github.com/noey2020/How-to-Talk-Probability-Review-1

https://github.com/noey2020/How-to-Talk-Generative-Approach-to-Classification

https://github.com/noey2020/How-to-Talk-of-Fitting-a-Distribution-to-Data-

https://github.com/noey2020/How-to-Talk-of-Host-of-Prediction-Problems

https://github.com/noey2020/How-to-Talk-of-Useful-Distance-Functions

https://github.com/noey2020/How-to-Talk-of-Improving-Nearest-Neighbor

https://github.com/noey2020/How-to-Talk-of-Prediction-Problems

https://github.com/noey2020/How-to-Talk-Matlab-Tricks-and-Tweaks

https://github.com/noey2020/How-to-Talk-Trading-and-Investing

https://github.com/noey2020/How-to-Work-in-Matlab-Development-Environment

https://github.com/noey2020/How-to-Talk-Vaccines

https://github.com/noey2020/How-to-Talk-Regression-in-Matlab

https://github.com/noey2020/How-to-Get-Started-in-Matlab

https://github.com/noey2020/How-to-Convert-Data-from-Web-Service-Using-Matlab

https://github.com/noey2020/Quote-for-the-Day

https://github.com/noey2020/How-to-Talk-Good-Investment-Strategy

https://github.com/noey2020/How-to-Talk-of-Good-Plan

https://github.com/noey2020/Thought-for-the-Day

https://github.com/noey2020/How-to-Talk-Stock-Watch-of-the-Day

https://github.com/noey2020/How-to-Talk-Data-Science

https://github.com/noey2020/How-to-Talk-Fundamental-Analysis

https://github.com/noey2020/How-to-Read-Company-Profiles

https://github.com/noey2020/How-to-Import-Data-from-Spreadsheets-and-Text-Files-Matlab-Without-Coding

https://github.com/noey2020/How-to-Talk-Model-of-Stock-Market-Prices-

https://github.com/noey2020/How-to-Talk-Digital-Wallets

https://github.com/noey2020/How-to-Talk-Investing

https://github.com/noey2020/How-to-Double-Your-Money-in-5years

https://github.com/noey2020/How-to-Talk-Matlab

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!
