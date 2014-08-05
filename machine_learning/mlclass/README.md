mlclass in IPython Notebooks
==================

Coursera Machine Learning Exercises in IPython Notebooks

> Just let me see it! These notebooks can be previewed using NBViewer http://nbviewer.ipython.org/github/adamwalz/mlclass_ipython/tree/master/notebooks/

This repository takes the matlab exercises from Andrew Ng's machine learning course and translates them to python using IPython notebooks, numpy, and matplotlib.

The pdf instructions that accompany each exercise are now embedded into the notebooks themselves. This helps students contextualize the instructions they are reading with the particular code block they will be working on.

Along the way, graphs and other visualizations will appear inline, and where appropriate they will utilize IPython interactive graphics to better understand where changing a variable parameter influences an algorithm.

I will not be posting solutions, as per Coursera's [Honor Code](http://help.coursera.org/customer/portal/articles/1164381-what-is-the-honor-code-), but have tried to provide hints where they are needed. This is especially true in area's where Numpy or Matplotlib are used heavily.

# Installation Requirements

These exercises require the following python packages

* [IPython 2.0](http://ipython.org)
* [Numpy](http://www.numpy.org)
* [Matplotlib](http://matplotlib.org)

Numpy can be a challenge to install, so I recommend one of the following python installations.

[SciPy Superpack](http://fonnesbeck.github.io/ScipySuperpack/) is a shell script for OS X 10.9 which installs along with many other useful packages such as scipy and scikit_learn. This installation uses the default OS X python 2.7.5

[Anaconda](http://continuum.io/downloads#27) is a larger install and includes many more packages you may find useful, but will not be necessary for this course. One upside to anaconda is that is does not use the system python or Xcode. It can also be installed on any operating system or with [python 3.4](http://continuum.io/downloads#34). Python 3 will be acceptable for this course.

# Running an IPython Notebook

Once you have the required packages installed and this repository cloned, navigate to the *notebooks* directory in your terminal and type `ipython notebook`.

This will start a notebook server and open your browser with a list of notebooks. Open the link to any of the exercise notebooks, and follow along with the directions in each one.
