# Optimising-Agricultural-Data
In this project, I have created a model that can suggest the farmer according to the soil condition and climate, to sow which crop to give maximum yields at lower cost.

# Language Used
Python-3.9.9

#Tools Used
Jupyter Notebook


# The Modules Used

## numpy
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

At the core of the NumPy package, is the ndarray object. This encapsulates n-dimensional arrays of homogeneous data types, with many operations being performed in compiled code for performance.
For more: https://numpy.org/doc/stable/user/whatisnumpy.html

## pandas
pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way towards this goal.
For more: https://pypi.org/project/pandas/

## matplotlib
Matplotlib is one of the most popular Python packages used for data visualization. It is a cross-platform library for making 2D plots from data in arrays. Matplotlib is written in Python and makes use of NumPy, the numerical mathematics extension of Python. It provides an object-oriented API that helps in embedding plots in applications using Python GUI toolkits such as PyQt, WxPythonotTkinter. It can be used in Python and IPython shells, Jupyter notebook and web application servers also.

Matplotlib has a procedural interface named the Pylab, which is designed to resemble MATLAB, a proprietary programming language developed by MathWorks. Matplotlib along with NumPy can be considered as the open source equivalent of MATLAB.sible.
For more: https://www.tutorialspoint.com/matplotlib/matplotlib_introduction.htm

## seaborn
Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures.

Seaborn helps you explore and understand your data. Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots. Its dataset-oriented, declarative API lets you focus on what the different elements of your plots mean, rather than on the details of how to draw them.
For more: https://seaborn.pydata.org/introduction.html

## ipywidgets
ipywidgets, also known as jupyter-widgets or simply widgets, are interactive HTML widgets for Jupyter notebooks and the IPython kernel.

Notebooks come alive when interactive widgets are used. Users gain control of their data and can visualize changes in the data.
For more: https://ipywidgets.readthedocs.io/en/latest/

# Using Unsupervised Machine Learning

## Clustering 

Here we are clustering our data to group different crop which can be grown in similar conditions.
Clustering is a concept that we use in Unsupervised learning.
here we are using K-Means clustering technique to create clusters.
For more details about clustering: https://www.analyticsvidhya.com/blog/2016/11/an-introduction-to-clustering-and-different-methods-of-clustering/

## Creating Predictive Model

Now, we are creating a predictive model based on our data, to create predictions for our purposes. We are using Logistic Regression algorithm for training our model, as it is used in statistical software to understand the relationship between the dependent variable and one or more independent variables by estimating probabilities using a logistic regression equation. For More information about Logistic regression: https://www.ibm.com/topics/logistic-regression


## Splitting Our dataset and Training our model

Now, we are splitting our dataset to train our model and test our model, and for this we are using sklearn library's train_test_split, To train our model we are using LogisticRegression() from sklearn library


## Evaluating Our Model

Here we are comparing our model predictions with the original answers using confusion matrix and then we are using classification report to check on precision and recall


# Hardware Requirements

1. min. dual core CPU with 2GHz clock speed
2. min. 4 GB RAM
