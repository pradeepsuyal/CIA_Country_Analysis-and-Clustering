### CIA_Country_Analysis-and-Clustering

### customers_for_marketing_segmentation-

## Table of CONTENTS 
---------------------
 * [Aim](#aim)
 * [Dataset used](#data)
 * [Exploring the Data](#viz)
   - [Matplotlib](#matplotlib)
   - [Seaborn](#seaborn)
 * [using KMeans for clustering](#conclusion)
 

## AIM:<a name="aim"></a>

Gain insights into similarity between countries and regions of the world by experimenting with different cluster amounts.

## Dataset Used:<a name="data"></a>

Dataset can been found at my repository

## Exploring the Data:<a name="viz"></a>

Here I will use pandas and seaborn visualization skills to determine if Fandango's ratings in 2015 had a bias towards rating movies better to sell more tickets.

**Matplotlib:**<a name="matplotlib"></a>
--------
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.You can draw up all sorts of charts(such as Bar Graph, Pie Chart, Box Plot, Histogram. Subplots ,Scatter Plot and many more) and visualization using matplotlib.

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install matplotlib:

     pip: pip install matplotlib

     anaconda: conda install matplotlib
     
     import matplotlib.pyplot as plt

for more information you can refer to [matplotlib](https://matplotlib.org/) official site

![matplotlib](https://eli.thegreenplace.net/images/2016/animline.gif)

**Seaborn:**<a name="seaborn"></a>
------
Seaborn is built on top of Python’s core visualization library Matplotlib. Seaborn comes with some very important features that make it easy to use. Some of these features are:

**Visualizing univariate and bivariate data.**

**Fitting and visualizing linear regression models.**

**Plotting statistical time series data.**

**Seaborn works well with NumPy and Pandas data structures**

**Built-in themes for styling Matplotlib graphics**

**The knowledge of Matplotlib is recommended to tweak Seaborn’s default plots.**

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install seaborn:

    pip: "pip install seaborn"*

    anaconda: " conda install seaborn"*
    import seaborn as sns
    
for more information you can refer to [seaborn](https://seaborn.pydata.org/) official site.

![seaborn](https://i.stack.imgur.com/uzyHd.gif)

## using KMeans for clustering:<a name="conclusion"></a>

K-Means Clustering, also known as Lloyd’s Algorithm, is an iterative, data-partitioning, Unsupervised Learning Algorithm used to assign n observations to exactly one of K clusters defined by their centroids, where K is chosen before the algorithm starts.

Clustering

The most basic definition of clustering is the technique of grouping data points together. It is an assumption that data points of the same group posses similar properties or features, whereas data points from different groups will have high dissimilarity. Clustering is an Unsupervised Learning Method and is commonly used for statistical data analysis in many fields. With clustering, we only try to investigate the structure of the data by grouping them.

steps for Kmeans

•Step 1: Choose the number of clusters k. ...

•Step 2: Select k random points from the data as centroids. ...

•Step 3: Assign all the points to the closest cluster centroid. ...

•Step 4: Recompute the centroids of newly formed clusters. ...

•Step 5: Repeat steps 3 and 4.

Stopping Criteria for K-Means Clustering

There are essentially three stopping criteria that can be adopted to stop the K-means algorithm:

•Centroids of newly formed clusters do not change

•Points remain in the same cluster

•Maximum number of iterations are reached

We can stop the algorithm if the centroids of newly formed clusters are not changing. Even after multiple iterations, if we are getting the same centroids for all the clusters, we can say that the algorithm is not learning any new pattern and it is a sign to stop the training.

Another clear sign that we should stop the training process if the points remain in the same cluster even after training the algorithm for multiple iterations.

Finally, we can stop the training if the maximum number of iterations is reached. Suppose if we have set the number of iterations as 100. The process will repeat for 100 iterations before stopping.

![KMeans](https://dashee87.github.io/images/kmeans_bad.gif)

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)

