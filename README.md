# Data-Wrangling
# Description

This tutorial will introduce the use of Python for statistical data analysis, using data stored as Pandas DataFrame objects. Much of the work involved in analyzing data resides in importing, cleaning and transforming data in preparation for analysis. Therefore, the first half of the course is comprised of a 2-part overview of basic and intermediate Pandas usage that will show how to effectively manipulate datasets in memory. This includes tasks like indexing, alignment, join/merge methods, date/time types, and handling of missing data. Next, we will cover plotting and visualization using Pandas and Matplotlib, focusing on creating effective visual representations of your data, while avoiding common pitfalls. Finally, participants will be introduced to methods for statistical data modeling using some of the advanced functions in Numpy, Scipy and Pandas. This will include fitting your data to probability distributions, estimating relationships among variables using linear and non-linear models, and a brief introduction to bootstrapping methods. Each section of the tutorial will involve hands-on manipulation and analysis of sample datasets, to be provided to attendees in advance.

The target audience for the tutorial includes all new Python users, though we recommend that users also attend the NumPy and IPython session in the introductory track.

### Student Instructions

For students familiar with Git, you may simply clone this repository to obtain all the materials (iPython notebooks and data) for the tutorial. Alternatively, you may [download a zip file containing the materials](https://github.com/fonnesbeck/statistical-analysis-python-tutorial/archive/master.zip). A third option is to simply view static notebooks by clicking on the titles of each section below.

## Outline

### [Introduction to Pandas][1]

* Importing data
* Series and DataFrame objects
* Indexing, data selection and subsetting
* Hierarchical indexing
* Reading and writing files
* Sorting and ranking
* Missing data
* Data summarization

### [Data Wrangling with Pandas][2]

* Date/time types
* Merging and joining DataFrame objects
* Concatenation
* Reshaping DataFrame objects
* Pivoting
* Data transformation
* Permutation and sampling
* Data aggregation and GroupBy operations

### [Plotting and Visualization][3]

* Plotting in Pandas vs Matplotlib
* Bar plots
* Histograms
* Box plots
* Grouped plots
* Scatterplots
* Trellis plots

### [Statistical Data Modeling][4]

* Statistical modeling
* Fitting data to probability distributions
* Fitting regression models
* Model selection
* Bootstrapping

## Required Packages

* Python 2.7 or higher (including Python 3)
* pandas >= 0.11.1 and its dependencies
* NumPy >= 1.6.1
* matplotlib >= 1.0.0
* pytz
* IPython >= 0.12
* pyzmq
* tornado

**Optional**: statsmodels, xlrd and openpyxl

For students running the latest version of Mac OS X (10.8), the easiest way to obtain all the packages is to install the [Scipy Superpack](http://bit.ly/scipy_superpack) which works with Python 2.7.2 that ships with OS X.

Otherwise, another easy way to install all the necessary packages is to use Continuum Analytics' [Anaconda](http://docs.continuum.io/anaconda/install.html).


## Statistical Reading List

[The Ecological Detective: Confronting Models with Data](http://www.amazon.com/Ecological-Detective-Confronting-Models-Data/dp/0691034974/ref=sr_1_1?s=books&ie=UTF8&qid=1372250186&sr=1-1&keywords=ecological+detective), Ray Hilborn and Marc Mangel

Though targeted to ecologists, Mangel and Hilborn identify key methods that scientists can use to build useful and credible models for their data. They don't shy away from the math, but the book is very readable and example-laden.

[Data Analysis Using Regression and Multilevel/Hierarchical Models](http://www.amazon.com/Analysis-Regression-Multilevel-Hierarchical-Models/dp/052168689X/ref=sr_1_1?s=books&ie=UTF8&qid=1372250274&sr=1-1&keywords=gelman), Andrew Gelman and Jennifer Hill

The go-to reference for applied hierarchical modeling.

[The Elements of Statistical Learning](http://www-stat.stanford.edu/~tibs/ElemStatLearn/), Hastie, Tibshirani and Friedman

A comprehensive machine learning guide for statisticians.
