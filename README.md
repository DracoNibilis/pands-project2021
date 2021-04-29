# pands-project2021
# Final Project 2021 - Analysis of  the Fisher’s Iris data set.
# Author: Magdalena Malik

-- DATASET
iris_csv.csv downloaded from - https://datahub.io/machine-learning/iris

-- DESCRIPTION OF THE DATASET
The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician, eugenicist, and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis. It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species. Two of the three species were collected in the Gaspé Peninsula "all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus" - https://en.wikipedia.org/wiki/Iris_flower_data_set

The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant:
- Iris-setosa, 
- Iris-virginica,
- Iris-versicolor.

The dataset contains a set of 150 records under five attributes:
- sepal length (in cm), 
- sepal width (in cm), 
- petal length (in cm), 
- petal width (in cm), 
- class.

The line 0 - is header containing description of each row // sepallength,sepalwidth,petallength,petalwidth,class // .

-- CODE - LIBRARY USED

List of libraries used in this code:
- pandas -  imported as pd - is a Python package for data science; it offers data structures for data manipulation and analysis.
- numpy - imported as np - is a library for the Python, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- matplotlib.pyplot - imported as plt - is a comprehensive library for creating static, animated, and interactive visualizations in Python.
- seaborn -  imported as sns -  is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.


--- STRUCTURE OF CODE

For user disposition there is menu, containing all the elements that code is doing. 
Menu will provide 4 choices for the user:
1 - to see 2 scatter plots of irises
2 - to generate 4 histograms (save into files as png )
3 - to generate summary.txt file 
4 - to quit the program.

Functions used in code:
 - show_scatter() - function based on seaborn library, which is generating two scatter plots of dataset
 - write_hist() - function based on seaborn library , which is generating four histograms of dataset and writing them to a file as a .png files
 - text_summary() - function that is generating summary file with information about the dataset

---- PLOTS

- scatter plots - compering data of sepals ( length and width) and petals ( length and width) from dataset, each scatter plot shows compering information,

- histograms - each histogram is representation of comparing data :
    - petallength
    - petalwidth
    - sepallength
    - sepalwidth


-- SUMMARY


--REFERENCES


