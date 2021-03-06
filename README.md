# Machine Learning and Statistics Assessment

<p align="center">
  <img src="https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/Images/C_Twisted_Doodles.png" />
</p>

## Project Description
This repository comprises two Jupyter Notebooks and the associated files required for Machine Learning and Statistics Assessment for Winter 21/22. This module (52954) is part of the [Higher Diploma in Science in Computing in Data Analytics](https://www.gmit.ie/higher-diploma-in-science-in-computing-in-data-analytics). Full details of the assessment are available [here](assessment.pdf).
<br>
<br>

## Repository Contents

 - [scikit-learn.ipynb](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) - A Jupyter Notebook providing an overview of the scikit-learn Python library and demonstrations of 3 machine learning algorithms the library offers. 
 - [scipy-stats.ipynb](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb) - A Jupyter Notebook providing an overview of the scipy-stats Python library and demonstrations its uses using ANOVA to test a hypothesis. 
 - [requirements.txt](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/requirements.txt) - containing information of the libraries, modules, packages and files needed to run the Jupyter notebooks with minimal configuration
 - [Data](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/tree/main/Data) - contains the [Housing dataset](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/Data/housing.csv) used for the [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) and the [Diet dataset](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/Data/Diet.csv) used for the [scipy-stats notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb).
 - [Images](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/tree/main/Images) -  Contains the images used here and in the two Jupyter Notebooks. 
 - [Files](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/assessment.pdf) - contains a pdf of the assessment requirements and marking scheme.
<br>

***

## [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb)
<br>

The [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) provides an overview of the [scikit-learn Python library](https://scikit-learn.org/stable/) and examines three algorithms - [Linear Regression](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.linear_model), [Decision Tree Regression](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html#sklearn.tree.DecisionTreeRegressor) and [K - Nearest Neighbours](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html#sklearn.neighbors.KNeighborsRegressor).
<br>

### *Challenges:*

The initial plan for this project element was to showcase an algorithm that worked best for regression, one best suited for classification and a third used for both.

In researching, I found that regression algorithms were taken for granted. The articles and repositories I reviewed tested and used five or six regression models in their analysis. This is partly a result of the ease with which the sci-kit learn Python library facilitates regression analysis. However, I felt that it was a case of trying everything to get the best fit. 

Depending on the objective of the regression modelling, that may suffice. But understanding the different regression modelling approaches and how they differ is fundamental to data analysis. So instead, I demonstrate three different regression algorithms applied to the same dataset.
<br>

### *Presentation:*
The [scikit-learn notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb) has three main areas
 - Overview of the [scikit-learn library](https://scikit-learn.org/stable/)
 - A review of the [dataset](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/housing.csv) to be used
 - Execution of the three regression algorithms
 
My research demonstrated several ways to complete each type of regression analysis. Some applied one or two regression algorithms and compared the accuracy of the results. However, the majority made an initial comparison of the accuracy of numerous regression algorithms and then proceeded with one or two for complete modelling. Both are presented here - showing the difference in code and replicating real-life applications.
<br>

### *Further Research:*
It is beyond the scope of the assessment, but I would like to demonstrate each approach without the use of the scikit-learn library. The purpose of this addition would be to develop my Python skills further and to contrast the lower-level coding in Python with the efficiency of the [scikit-learn library](https://scikit-learn.org/stable/).
<br>
***

## [scipy-stats notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb)
<br>

The [scipy-stats notebook](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb) provides an overview of the [scipy.stats Python library]( https://docs.scipy.org/doc/scipy/reference/stats.html).
The library is then used to complete a hypothesis test using [ANOVA](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html).
<br>

### *Challenges:*
Similar to the selection process for the scikit-learn algorithms, it was essential to identify an appropriate dataset for the ANOVA test. And, to understand the purpose of the ANOVA test to be completed: one-way, two-way or repeated measures etc. Therefore, the dataset selected offered the potential for one-way and two-way ANOVA tests to satisfy the assumptions underlying ANOVA based on the research question identified.

I found the most challenging part of this problem was visually representing the outcomes of the test. The statistical output of the test is very informative, but visualisations of the test outputs would make it more accessible to readers.
<br>

### *Presentation:*
The [scipy-stats notebook]( https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb) has two main areas
 - Overview of the [scipy.stats Python library](https://docs.scipy.org/doc/scipy/reference/stats.html)
 - Testing a hypothesis using the [Diet dataset](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/Data/Diet.csv) and ANOVA testing.

A new variable is created to facilitate the ANOVA test, and descriptive statistical analysis and analysis of interactions between three variables are completed.
<br>

### *Further Research:*
While I didn't get to it during this project, I would like to complete more analysis on this dataset.
First, using a t-test to verify if participants lose weight. Second, using [ANCOVA]( https://stackoverflow.com/questions/2916760/ancova-in-python-with-scipy-numpy-stats). ANCOVA looks for statistically significant difference (covariance) between the means of 3 or more variables. This dataset would be suitable for that analysis(https://www.statology.org/ancova-python/). 
<br>
***

## Prerequisites for the Project
The [requirements.txt](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/requirements.txt) file specifies the packages required to run the notebooks.
To complete the assessment, I installed the full Anaconda package from https://www.anaconda.com.

The packages used in this repository (detailed below) are all part of the Anaconda package:

 - Jupyter Notebook - Available via https://anaconda.org/anaconda/jupyter or https://jupyter.org/
 - NumPy package - Available via https://anaconda.org/anaconda/numpy or https://numpy.org/
 - Seaborn - Available via https://anaconda.org/anaconda/seaborn or https://seaborn.pydata.org/
 - Matplotlib - Available via https://anaconda.org/anaconda/matplotlib or https://matplotlib.org/
 - Pandas - Available via https://anaconda.org/anaconda/pandas or https://pandas.pydata.org/
<br>

***

## Accessing and Running the Jupyter Notebooks
<details><summary>How to download or clone a GitHub repository</summary>
<br>
You can download or clone a GitHub repository to run the Jupyter Notebooks. Downloading the repository will provide access to the notebooks and the associated files locally on your device.
    
Download Repository
 - Click on the green "Code" button
 - Select "Download ZIP" from the selection menu that appears 
    
 ![image](https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/Images/download_zip_file_of_github_repository.png)

Cloning the Repository
    
 - From your machine's command line, run the command below command to clone the repository locally to your machine:
 - git clone https://github.com/SharonNicG/52954-Machine-Learning-and-Statistics.git
</details>
<br>

<details><summary>Launching and Running a Jupyter Notebook</summary>
<br>
Jupyter is a Python package and does not require separate importation from Python packages. It commonly runs from the machine command line.

To launch a Jupyter notebook, open your terminal/command line and navigate the directory where you have saved the pulled repository containing the Jupyter Notebook. Typing the command 'Jupyter Notebook' into the terminal/command line creates an instance of Jupyter on a local server.

When Jupyter Notebook has been called from the terminal/command line, a browser window should open, showing the Jupyter Notebook interface. If it does not, you can copy the URL presented in the terminal/command line and paste this into your browser's address bar.

Once you have accessed the Jupyter Notebook interface, you can view the files in the current directory. Clicking on the files will open them. Jupyter notebook files are identifiable by their notebook icon (within the Jupyter Notebook interface and by the file extension .ipynb

You can run each cell in the notebook by pressing shift + enter on each row. Alternatively, you can run the whole notebook in a single step by clicking on the menu 'Cell' and selecting 'Run All'.

Terminate the browser tab by clicking the "X" in the top right corner to close the notebook. To stop the instance on the local server and shut down the Jupyter kernel, press control-C in the terminal/command line.

The above steps should allow the Jupyter Notebook to display automatically (assuming the prerequisites from [requirements.txt]{} were met). Jupyter Notebooks can also be rendered by pasting the URL presented in the terminal/command line on the site https://nbviewer.jupyter.org/. 
</details>
<br>

<details><summary>How to view Jupyter Notebooks using NBViewer</summary>
NBViwer renders Jupyter Notebook, so they are accessible via a URL. The cells cannot be interacted with as in a live Jupyter Notebook. 
  
- The scikit-learn notebook is available on NBViewer by clicking this badge [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scikit-learn.ipynb)
  
- The scipy.stats notebook is available on NBViewer by clicking this badge [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/SharonNicG/52954-Machine-Learning-and-Statistics/blob/main/scipy-stats.ipynb)
  
</details>
<br>

<details><summary>How to view Jupyter Notebooks using Binder</summary>
Binder hosts Jupyter Notebooks online, allowing users to still interact with the cells as in a live notebook. 
  
 - The scikit-learn notebook is available on Binder by clicking this badge [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SharonNicG/52954-Machine-Learning-and-Statistics/HEAD?labpath=https%3A%2F%2Fgithub.com%2FSharonNicG%2F52954-Machine-Learning-and-Statistics%2Fblob%2Fmain%2Fscikit-learn.ipynb)
  
 - The scipy.stats notebook is available on Binder by clicking this badge [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SharonNicG/52954-Machine-Learning-and-Statistics/HEAD?labpath=https%3A%2F%2Fgithub.com%2FSharonNicG%2F52954-Machine-Learning-and-Statistics%2Fblob%2Fmain%2Fscipy-stats.ipynb)
  
</details>
<br>

## Credits
 - Statistics Illustration <a href="https://twitter.com/twisteddoodles">Twisted Doodles</a> at <a href="https://twitter.com/twisteddoodles/status/960801583012380672">twitter.com/twisteddoodles/</a>.
  - Scikit-learn Logo <a href="https://commons.wikimedia.org">WikiMedia</a> at <a href="https://commons.wikimedia.org/wiki/File:Scikit_learn_logo_small.svg">https://commons.wikimedia.org/wiki/File:Scikit_learn_logo_small.svg</a>.
 - Boston Landscape Photo <a href="https://unsplash.com/@michaelwb?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Michael Browning</a> on <a href="https://unsplash.com/s/photos/boston?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>.
 - K-Nearest Neighbour Image <a href="https://www.datacamp.com">Datacamp</a> at <a href="https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn">https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn/</a>.
 - Linear Regression Image <a href="https://www.analyticsvidhya.com/">Analytics Vidya</a> at <a href="https://www.analyticsvidhya.com/blog/2021/05/5-regression-algorithms-you-should-know-introductory-guide/g">https://www.analyticsvidhya.com/blog/2021/05/5-regression-algorithms-you-should-know-introductory-guide/</a>.
 - Decision Tree Image <a href="https://www.javatpoint.com/">Java Point</a> at <a href="https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm">https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm/</a>.
  - SciPy Logo <a href="https://commons.wikimedia.org">WikiMedia</a> at <a href="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/SCIPY_2.svg/480px-SCIPY_2.svg.png">https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/SCIPY_2.svg/480px-SCIPY_2.svg.png</a>.
  - Diet Dataset Photo <a href="https://unsplash.com/@dbtownsend?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">David B Townsend</a> on <a href="https://unsplash.com/s/photos/positive-diet?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
 - As with so many of my projects, I have relied upon the faithful users of [StackOverflow](https://stackoverflow.com/). Where relevant, StackOverflow pages are cited in the reference section of the notebooks. But for resolutions to minor issues (that may have derailed me for hours) and for the comfort in knowing someone else has made the same mistake, I thank them. 
<br>

***
# End
