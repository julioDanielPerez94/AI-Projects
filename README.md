# AI-Projects
This repository will include projects that I've done during my learning journey in machine learning, deep learning and AI in general.

# Spain_salary_analysis_2008-2017
Motivation
This is my first project for my Udacity Data Scientist Nanodegree Course. In this case my goal is to analyze a dataset applying CRISP-DM process.

Spain salary analysis 2008-2017
In this project you will find a quite complete analysis of the situation of salaries in Spain. You can find comparisons of salaries by states and gender, which is a topical issue. You will be able to see if the gap payment between male and females is big or small, as well as salaries of differents states. Finally we use the ARIMA model to forescast salary from 2017 onwards.

Files in this repository
Pictures: there are some picture of charts which were saved from the notebook
spain_salary_distribution.csv: the dataset to analyze
Project_1_udacity.ipynb: the notebook of the project
Installation and packages
You will not need to install any new module. You just need to copy the following lines to import the necessary packages:

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
sns.set() # we apply the seaborn style to our charts

#To use ARIMA model to time series analysis
from statsmodels.tsa.arima.model import ARIMA
Results
You can find thew results in this post. Here

Issues
Nothing to comment here.

References
Matplotlib example charts

StackOverflow

Machinelearningmastery.com

Arima Model Documentation

Pandas

Numpy

Seaborn

Kaggle

License
You can find the Licensing for the data and other descriptive information at the Kaggle link available here. Otherwise, feel free to use the code here as you would like!

# Working hours and flights analysis for my airline company (Binter)
Motivation
This is just a entertaining try to use some data from my company and to build a regression model to try to predict the productivity.

Flights vs working hours
In this project you will find a extense analysis of a dataset that includes some data cleansing and data wrangling. Then we continue with some charts and we buildsome models. First trying withe statsmodel package and finally with sklearn package. After that, we analyse the variability of the data using time series forecasting (Sarimax used in this case). The time series analysis was guided by Susan Li article, which is in References

Files in this repository
Csv file
Python notebook with all the chunks of code
Installation and packages
You just need to copy the following lines to import the package and you will be able to reproduce all the content:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
import itertools
sns.set()
Results
The results are shown in the differents charts of the notebook. The models seems to be working nicely but we can improve their performance for sure.

Issues
Nothing to comment here. All is working properly

References
StackOverflow

Towards Data Science - Susan Li Article

License
Feel free to use the code here as you would like!
