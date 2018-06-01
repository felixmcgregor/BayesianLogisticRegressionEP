# BayesianLogisticRegressionEP
Implementation of Bayesian Logistic Regression using Expectation Propagation for approximate inference.

This repository contains some code for Expectation Propagation applied to the clutter problem and logistic regression. 

Simon Barthelmé also gives a very nice talk which can be found on youtube:
https://www.youtube.com/watch?v=0tomU1q3AdY&t=1298s
and I reccommend Minka's lecture:
http://videolectures.net/mlss09uk_minka_ai/?q=minka

Jose's slides has very nice formulas for the clutter problem and there is a notebook implementing the clutter problem.

The book Bayesian Data Analysis discusses EP applied to logistic regression. "Expectation Propagation as a Way of Life" and the Masters thesis were of the most useful resources to better EP on logistic regression by exploiting dimension reduction. There is a notebook implementing logistic regression from Bayesian Data Analysis.

There are 2 notebooks for memory optimised EP where factors are stored in one dimension. The first nicely visualises logistic regression with EP on the iris dataset and includes visualisation of prediction methods. The second notebook (a bit messier) trains on a scaled MNIST classes 3, 5 and 8 and tests the accuracy with sampling.

Everything is coded in Python 2.7 using mostly NumPy and Scipy. Scikit Learn, Matplotlib and Pandas are also needed for some data preparation and visualisation. 
