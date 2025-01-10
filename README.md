# Python-EDA-Project
𝗘𝘅𝗽𝗹𝗼𝗿𝗮𝘁𝗼𝗿𝘆 𝗗𝗮𝘁𝗮 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀 (𝗔𝗰𝗮𝗱𝗲𝗺𝗶𝗰 𝗣𝗿𝗼𝗷𝗲𝗰𝘁)
𝗘𝘅𝗽𝗹𝗼𝗿𝗮𝘁𝗼𝗿𝘆 𝗱𝗮𝘁𝗮 𝗮𝗻𝗮𝗹𝘆𝘀𝗶𝘀 𝗽𝗿𝗼𝗷𝗲𝗰𝘁 𝘂𝘀𝗶𝗻𝗴 𝗽𝗼𝘄𝗲𝗿𝗳𝘂𝗹 𝗣𝘆𝘁𝗵𝗼𝗻 𝗽𝗮𝗰𝗸𝗮𝗴𝗲𝘀 𝗮𝗻𝗱 𝗹𝗶𝗯𝗿𝗮𝗿𝗶𝗲𝘀.

𝗨𝘀𝗲 𝗰𝗮𝘀𝗲: The data is taken randomly from a company with 200 samples

𝗖𝗼𝗹𝘂𝗺𝗻𝘀: Email, Address, Avatar, Avg. Session Length, Time on App, Time on Website, Length of Membership, Yearly Amount Spent.
𝗠𝗼𝗱𝗲𝗹: 𝗦𝗶𝗺𝗽𝗹𝗲 𝗟𝗶𝗻𝗲𝗮𝗿 𝗥𝗲𝗴𝗿𝗲𝘀𝘀𝗶𝗼𝗻 𝗮𝗹𝗴𝗼𝗿𝗶𝘁𝗵𝗺 𝗶𝘀 𝘂𝘀𝗲𝗱

𝗣𝗮𝗰𝗸𝗮𝗴𝗲𝘀 𝘂𝘀𝗲𝗱:
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn import metrics
from sklearn import linear_model
from sklearn.metrics import mean_absolute_error, mean_squared_erro

𝗷𝗼𝗶𝗻𝘁𝗽𝗹𝗼𝘁
yearly amount spent vs time spent on website, we see the data with marginal bins. There is a relationship means there is time spent variation with yearly amount spent.

𝗽𝗮𝗶𝗿𝗽𝗹𝗼𝘁: 
(it's robust to see each feature's relationship and spread over the data points) We see multiple scatter plots.
the data as we see points are scattered with minimal space and similarly histplots showing symmetric shape which means data is at near the mean that can help to minimize distance from centre and reduce residual error. similarly, more chances to good model fit.
we can consider it the shape is with gaussian normal distribution assumptions tells that data is normally distributed.

𝗹𝗺𝗽𝗹𝗼𝘁:
we draw scatterplot with regression line to check the relationship of yearly membership and yearly amount spent
there is positive relationship because datapoints are near the line and less standard error, model in underfit either overift.
means amount is spend yearly for membership 

𝗦𝗽𝗹𝗶𝘁 𝗱𝗮𝘁𝗮:
then we split the data by test15% and 85% train
numerical features of customers, and variable y to the "Yearly Amount Spent" column. we fit the model and check correlation coefficients and we see 2 features are in +1 means positive correlation and remaining 3 are with negative correlation.

𝗠𝗼𝗱𝗲𝗹 𝗽𝗿𝗲𝗱𝗶𝗰𝘁𝗶𝗼𝗻:
then we predict our model and test it's accuracy on a scatter plot, to see the difference between predicted and actual values. we can see the Mean absolute error, mean squared error, root mean squared error and we see the values are small that means less errors and more fit of our model.

𝗣𝗿𝗲𝗱𝗶𝗰𝘁-𝗔𝗰𝘁𝘂𝗮𝗹
Laslty we draw histogram for to y test - y predict means we subtract the test from predict values to see the distance and difference of errors. it's kind of normal.

This project gave me a powerful exploration of data either for further data operations or initial statistical analysis which is the backbone before going further. We cannot move in any data without an Exploratory Data Analysis Cycle.
