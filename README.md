# MachineLearning
All labs for machine learning course

## Simple Linear Regression
Simple linear regression is the most basic model in machine learning
where we fit a scalar variable `y` from another scalar variable `x` through
a linear model.
* [Lab: Boston housing data](lab_housing_partial.ipynb) 

## Logistic Regression
Logistic regression is a widely-used classifier that provides a good
introduction to linear classifiers.  
* [Lab: Genetic analysis of Down's syndrome in mice](./lab_gene_partial.ipynb)

## Model selection and regularization
A key issue in statistical modeling is to determine the suitable complexity
of the model to use.  More complex models can capture more of the relationship
between the predictors and target variable.  But, using more complex models risks
over-fitting.
* [Lab: Neural decoding motor cortex signals](./lab_neural_partial.ipynb)

## Multiple Linear Regression
In multiple linear regression, we fit a scalar variable `y` from 
a vector of predictors  `x=[x[0],...,x[k-1]]` through
a linear model of the form:
~~~python
   yhat = beta[0] + beta[1]*x[0] + ... + beta[k]*x[k-1]
~~~
* [Lab: Calibrating robot dynamics](lab_robot_calib_partial.ipynb) To be completed by the student.

## Unit 5:  Numerical optimization
Most machine learning problems come down to performing some form of numerical
optimization to find parameters that minimize a loss function representing
how well the model fits the data.  In this section, we show how to build
a simple numerical optimizer from scratch.  We also demonstrate how to 
compute gradient in python, which are key to performing the optimization.
* [Lab 5: Audio pitch detection](./lab_audio_partial.ipynb)

## Unit 6:  Support Vector Machines (SVMs)
The [support vector machine](https://en.wikipedia.org/wiki/Support_vector_machine) 
is one of the most basic and widely-used classification tools.  
When combined with the kernel trick, SVMs can perform nonlinear classification
and have been successful in a wide range of tasks.
* Lab 6: Extended MNIST 

## Unit 7:  Neural Networks
In this unit, we provide an introduction to simple neural networks
with a single hidden layer.  Understanding these networks will provide the
basis for working with deep networks that will be explored in the next unit.
Before doing the demos and labs in this unit, you will need to:
*  Install a deep learning *backend*, such as [Tensorflow](https://www.tensorflow.org/install/)
*  Install [Keras](https://keras.io/#installation) which runs on top of the
deep learning backend.
* [Lab 7:  Music instrument classification](./lab07_music_partial.ipynb)


## Unit 8:  Convolutional and Deep Neural Networks
Convolutional and deep neural network have had trememndous success in machine
learning, particularly for image and text problems.  In this unit, we
provide a very brief introduction to these networks.  
* Lab 8:  Transfer learning with a pre-trained network

## Unit 9:  Principal Component Analysis
PCA is one of the most fundamental tools in dimensionality reduction.
* [Lab 9: Movie recommendations](./lab09_movies_partial.ipynb)
