# DSND Capstone Project - Starbucks Capstone Challenge
This file is a documentation file for the exercise performed as a part of Data Scientist NanoDegree Capstone Project - Starbucks Capstone Challenge. 

Purpose of this project is to write a blog that will be supported by data science exercise. In this file I will describe most useful information related to files I have uploaded to the repository. Files included are:

  - Starbucks_Capstone_notebook.ipynb - jupyter notebook.
  - Starbucks_Capstone_notebook.html - jupyter notebook exported to html file.
  - licence file.
  - data.zip - zip file with data json files used in this exercise.
 
## Data
Data is avialable in the zip file attached to this project.

## Purpose and intent
Purpose of this excercise is to find answer to 2 questions (provide 2 insights):

1. Identify several groups of customers (clusters) and relation of these groups to the promotion?
Each Starbucks customer responds differently to offered promotions. First task therefore would be to group customers pools based on their responses and demography info. KMeans algorithm will be used to group these people.

2. What can be recommended to the marketing team based on analysis above?


## Code
Data analysis was executed in a Jupyter notebook that operates on Python 3 Kernel (Anaconda). Python libraries used for this project includes:

* numpy - https://numpy.org/
* pandas - https://pandas.pydata.org/
* pyplot - https://matplotlib.org/api/pyplot_api.html
* sklearn modules: sklearn.cluster, sklearn.decomposition, sklearn.preprocessing - https://scikit-learn.org/stable/
* seaborn - https://seaborn.pydata.org/


## Analytics Process
Process outlied in the Project file follows CRISP-DM Process (Cross Industry Process for Data Mining). You can see inside the file that multiple steps were taken to prepare data: drop nan values, change data types, or remove special characters from the data. File was documented with comments therefore each step has instruction associated with it. 

## Outcome of the analysis
Analysis has provded answer to 2 business questions. You are encuraged to dive more into the dataset. More details can be found in my medium post.

