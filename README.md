# How-to-Talk-scikit-learn-Machine-Learning-Library

January 15, 2021

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me! 😊

We've had an incredible mathematical tour of machine learning. We learned about data, and how to derive parameters representing our data, and
how to optimize our loss/cost functions by the popular least square regression. We rewrote the summation loss function into matrix vector
format as in: Wtranspose dot product X. W is the coefficient matrix while the X is feature vector. When there are multiple dimensions for
features we created covariance and correlation matrices. We analyze correlation between features, rank them, select and extract. We will 
eventually settle for a high correlation of features that will exhibit good variance & good correlation. Those which are uncorrelated we dispose
and throw out as unmeaningful features.

Via the convenient Wtranspose dot product X format, we used NumPy arrays and Pandas dataframe.

We also talked about optimizing loss functions and the many tools & options we have at our disposal.

For example, regularization is a very useful method for handling collinearity (high correlation among features), filtering out noise from data,
and eventually preventing overfitting.

The concept behind regularization is to introduce additional information (bias) to penalize extreme parameter (weight) values. The most
common form of regularization is so-called L2 regularization (sometimes also called L2 shrinkage or weight decay).

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

However, even more important than the choice of an appropriate learning algorithmis the available  data in our training dataset. No algorithm will be
able to make good predictions without informative and discriminatory features.

Next, we will discuss important topics regarding the preprocessing of data, feature selection, and dimensionality reduction, which means that we will
need to build powerful machine learning models.

In a nutshell to what's next, we aim to select meaningful features. If we notice that a model performs much better on a training dataset than on the
test dataset, this observation is a strong indicator of overfitting. As we discussed earlier, overfitting means the model fits the parameters too
closely with regard to the particular observations in the training dataset, but does not generalize well to new data; we say that the model has a 
high variance. The reason for the overfitting is that our model is too complex for the given training data. Common solutions to reduce the
generalization error are as follows:

• Collect more training data

• Introduce a penalty for complexity via regularization

• Choose a simpler model with fewer parameters

• Reduce the dimensionality of the data

Tune in to the next "How to Talk ...".

I included some jupyter notebooks to serve as study guide and to practice on real python code.

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
