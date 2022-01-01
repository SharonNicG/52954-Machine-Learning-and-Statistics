# Machine Learning and Statistics Assessment

## Project Description
This repository comprises two (2) Jupyter Notebooks and the associated files required for Machine Learning and Statistics Assessment for Winter 21/22. This module (52954) is part of the [Higher Diploma in Science in Computing in Data Analytics](https://www.gmit.ie/higher-diploma-in-science-in-computing-in-data-analytics). Full details of the assessment are available [here](assessment.pdf).
<br />
<br />

## Repository Contents

 - [assessment.pdf](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/assessment.pdf)
 - [scikit-learn.ipynb](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) - A Jupyter Notebook providing and overview of the scikit-learn Python library and demonstrations of 3 machine learning algorithms the library offers. 
 - [scipy-stats.ipynb](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb) - A Jupyter Notebook providing and overview of the scipy-stats Python library and demonstrations its uses using ANOVA to test a hypothesis. 
 - [Data](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/tree/main/Data) - contains the [Housing dataset](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/Data/housing.csv) used for the [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) and the [Diet datset]() used for the [scipy-stats notebook]( https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb)
 - [Images]() -  Contains the images that are used here and in the two Jupyter Notebooks. 
 - [requirements.txt](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/requirements.txt) - containing information of the libraries, modules, packages and files needed to run the Jupyter notebooks with minimal configuration

## scikitlLearn.ipynb

The [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) provides an overview of the [scikit-learn Python library](https://scikit-learn.org/stable/) and examines three (3) of its algorithms - [Linear Regression](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.linear_model), [Decision Tree Regression](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html#sklearn.tree.DecisionTreeRegressor) and [K - Nearest Neighbours](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html#sklearn.neighbors.KNeighborsRegressor).
<br />
<br />

### Challenges:

The initial plan for this project element was to showcase an algorithm that worked best for regression, one best suited for classification and a third used for both.

In researching, I found that regression algorithms were taken for granted. The articles and repositories I reviewed tested and used five (5) or six (6) regression models in their analysis. This is partly a result of the ease with which the sci-kit learn Python library facilitates regression analysis. However, I felt that it was a case of trying everything to get the best fit. 

Depending on the objective of the regression modelling, that may suffice. But having a better understanding of the different regression modelling approaches and how they differ is fundamental to data analysis. So instead, I demonstrate three (3) different regression algorithms applied to the same dataset.
<br />
<br />

### Presentation:
The [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) has three (3) main areas
 - Overview of the [scikit-learn library](https://scikit-learn.org/stable/)
 - A review of the [dataset](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/housing.csv) to be used
 - Execution of the three (3) regression algorithms
 
You can also access this notebook via NBViewer:
**insert badge**

Or you can view an interactive version via Binder:
**insert badge**
 
My research demonstrated several ways to complete each type of regression analysis. Some applied one (1) or two (2) regression algorithms and compared the accuracy of the results. However, the majority made an initial comparison of the accuracy of numerous regression algorithms and then proceeded with one (1) or two (2) for complete modelling. Both are presented here - showing the difference in code and replicating real-life applications.
<br />
<br />

### Further Research:
It is beyond the scope of the assessment, but I would like to demonstrate each approach without the use of the scikit-learn library. The purpose of this addition would be to develop my Python skills further and to contrast the lower-level coding in Python with the efficiency of the [scikit-learn library](https://scikit-learn.org/stable/).
<br />
<br />
***
The [scipy-stats notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb) provides an overview of the [scipy.stats Python library]( https://docs.scipy.org/doc/scipy/reference/stats.html).
The library is then used to complete a hypothesis test using [ANOVA](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html)
<br />
<br />

### Challenges:
Similar to the selection process for the scikit-learn algorithms, it was essential to identify an appropriate dataset for the ANOVA test. And, to understand the purpose of the ANOVA test to be completed: one-way, two-way or repeated measures etc.
The dataset selected offered the potential for one-way and two-way ANOVA tests to satisfy the assumptions underlying ANOVA based on the research question identified.
I found the hardest part of this problem was visually representing the outcomes of the test. The statistical output of the test is very informative, but visualisations of the test outputs would make it more accessible to readers.
<br />
<br />

### Presentation:
The [scipy-stats notebook]( https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb) has two main areas
 - Overview of the [scipy.stats Python library](https://docs.scipy.org/doc/scipy/reference/stats.html)
 - Testing of a hypothesis using the [Diet dataset] (https://www.sheffield.ac.uk/polopoly_fs/1.570199!/file/stcp-Rdataset-Diet.csv) and ANOVA testing.

You can also access this notebook via NBViewer:
**insert badge**

Or you can view an interactive version via Binder:
**insert badge**

A new variable is created to facilitate the ANOVA test, and descriptive statistical analysis and analysis of interactions between three variables are completed.
<br />
<br />

### Further Research:
While I didn’t get to it during this project, I would like to complete more analysis on this dataset.
First, using a t-test to verify if participants lose weight. Second using [ANCOVA]( https://stackoverflow.com/questions/2916760/ancova-in-python-with-scipy-numpy-stats, https://www.statology.org/ancova-python/). ANCOVA looks for statistically significant difference (covariance) between the means of 3 or more variables. This dataset would be suitable for that analysis. 
 analysis of covariance used to determine whether or not there is a statistically significant difference between the means of three or more independent groups
<br />
<br />

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

The above steps should allow the Jupyter Notebook to display automatically (assuming the prerequisites from [requirements.txt]{} were met). Jupyter Notebooks can also be rendered by pasting the URL presented in the terminal/command line on the site https://nbviewer.jupyter.org/. 

### Viewing the notebooks via NBViewer
Both notebooks are also available via NBViewer. This renders the notebook so that it can be accessed via a URL, although the cells cannot be interacted with like in a live Jupyter Notebook. You can find the NBViewer links via the buttons at the top of the two notebooks, or in the Repository Contents section above.

### Viewing the notebooks via Binder
Similar to NBViewer, Binder allows us to host our Jupyter Notebooks online while allowing users to still interact with the cells. You can find the URLs for the two notebooks in Binder via the buttons at the top of the two notebooks or in the Repository Contents section above.

## Credits
As with so many of my projects, I have relied upon the faithful users of [StackOverflow](https://stackoverflow.com/). Where relevant, StackOverflow pages are cited in the reference section of the notebooks. But for resolutions to minor issues (that may have derailed me for hours) and for the comfort in knowing someone else has made the same mistake, I thank them. 

## References
1. [Jupyter - Installing Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html)
2. [Jupyter - nbviewer](https://nbviewer.jupyter.org/)

***
# End