# keras-nbsvm

This is the source code for the tutorial:

> [**A Neural Implementation of NBSVM in Keras**](http://test/test) 

NBSVM is a text classification model proposed by Wang and Manning in 2012 that takes a linear model such as SVM (or logistic regression) and infuses it with Bayesian probabilities by replacing word count features with Naive Bayes log count ratios.  Despite its simplicity, NBSVM models have been shown to be both fast and powerful across wide range of different text classification datasets.  In this notebook, we cover the following:

* An NBSVM model is implemented as a neural network using the deep learning framework, *Keras*.
* Using the well-studied IMDB movie review dataset, we show that this Keras implementation achieves a test accuracy of **92.5%** with only a few seconds of training.  This is competitive with deeper and more sophisticated neural network architectures that take much longer to train.



### Requirements

The following software/libraries should be installed:

- [Python 3](https://www.python.org/) (tested on 3.6.7)
- [Keras](https://keras.io/)  (tested on 2.2.2)
- [scikit-learn](https://scikit-learn.org/stable/) (tested on 0.20.0)
