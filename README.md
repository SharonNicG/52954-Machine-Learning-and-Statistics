# Machine Learning and Statistics Assessment
***

## Project Description
This repository comprises two (2) Jupyter Notebooks and the associated files required for Machine Learning and Statistics Assessment for Winter 21/22. This module (52954) is part of the [Higher Diploma in Science in Computing in Data Analytics](https://www.gmit.ie/higher-diploma-in-science-in-computing-in-data-analytics). Full details of the assessment are available [here](assessment.pdf).


### scikitlLearn.ipynb

The [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) provides an overview of the [scikit-learn Python library](https://scikit-learn.org/stable/) and examines three (3) of its algorithms - [Linear Regression](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.linear_model), [Decision Tree Regression](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html#sklearn.tree.DecisionTreeRegressor) and [K - Nearest Neighbours](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html#sklearn.neighbors.KNeighborsRegressor).

#### Challenges:

The initial plan for this project element was to showcase an algorithm that worked best for regression, one best suited for classification and a third used for both.

In researching, I found that regression algorithms were taken for granted. The articles and repositories I reviewed tested and used five (5) or six (6) regression models in their analysis. This is partly a result of the ease with which the sci-kit learn Python library facilitates regression analysis. However, I felt that it was a case of trying everything to get the best fit. 

Depending on the objective of the regression modelling, that may suffice. But having a better understanding of the different regression modelling approaches and how they differ is fundamental to data analysis. So instead, I demonstrate three (3) different regression algorithms applied to the same dataset.

#### Presentation:
The [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) has three (3) main areas
 - Overview of the [scikit-learn library](https://scikit-learn.org/stable/)
 - A review of the [dataset](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/housing.csv) to be used
 - Execution of the three (3) regression algorithms
 
My research demonstrated several ways to complete each type of regression analysis. Some applied one (1) or two (2) regression algorithms and compared the accuracy of the results. However, the majority made an initial comparison of the accuracy of numerous regression algorithms and then proceeded with one (1) or two (2) for complete modelling. Both are presented here - showing the difference in code and replicating real-life applications.

#### Further Research:
It is beyond the scope of the assessment, but I would like to demonstrate each approach without the use of the scikit-learn library. The purpose of this addition would be to develop my Python skills further and to contrast the lower-level coding in Python with the efficiency of the [scikit-learn library](https://scikit-learn.org/stable/).

Full details available [here](assessment.pdf).

***
## Prerequisites for the Project
To complete the assignment, I installed the full Anaconda package from https://www.anaconda.com.

The packages used in this repository (detailed below) are all part of the Anaconda package:

 - Jupyter Notebook - Available via https://anaconda.org/anaconda/jupyter or https://jupyter.org/
 - NumPy package - Available via https://anaconda.org/anaconda/numpy or https://numpy.org/
 - Seaborn - Available via https://anaconda.org/anaconda/seaborn or https://seaborn.pydata.org/
 - Matplotlib - Available via https://anaconda.org/anaconda/matplotlib or https://matplotlib.org/
 - Pandas - Available via https://anaconda.org/anaconda/pandas or https://pandas.pydata.org/

## Running a Jupyter Notebook
Jupyter is a Python package and does not require importation from Python packages. It commonly runs from the machine command line.

To launch a Jupyter notebook, open your terminal/command line and navigate the directory where you have saved the pulled Jupyter Notebook. Typing the command Jupyter Notebook into the terminal/command line creates an instance of Jupyter on a local server.

When Jupyter Notebook has been called from the terminal/command line, a browser window should open, showing the Jupyter Notebook interface. If it does not, you can copy the URL presented in the terminal/command line and paste this into your browser's address bar.

Once you have accessed the Jupyter Notebook interface, you can view the files in the current directory. Clicking on the files will open them. Jupyter notebook files are identifiable by their notebook icon (within the Jupyter Notebook interface and by the file extension .ipynb

Terminate the browser tab by clicking the "X" in the top right corner to close the notebook. To stop the instance on the local server and shut down the Jupyter kernel, press control-C in the terminal/command line.

The above steps should allow the Jupyter Notebook to display automatically (assuming the prerequisites were met). Jupyter Notebooks can also be rendered by pasting the URL presented in the terminal/command line on the site https://nbviewer.jupyter.org/. 

## Contents of Repository

 - [assessment.pdf](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/assessment.pdf)
 - [scikit-learn.ipynb](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb)
 - [housing.csv](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/housing.csv) - the dataset used for the [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb)
 - requirements.txt - information of the libraries, modules, packages and files needed to run the Jupyter notebooks with minimal configuration

scipy-stats.ipynb

## References
1. [Jupyter - Installing Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html)
2. [Jupyter - nbviewer](https://nbviewer.jupyter.org/)

***
# End