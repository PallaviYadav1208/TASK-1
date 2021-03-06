# TASK-1
# LINEAR-REGRESSION
Linear regression is a regression model that uses a straight line to describe the relationship between variables. It finds the line of best fit through your data by searching for the value of the regression coefficient(s) that minimizes the total error of the model.
# DataSet
The dataset contains observations about income (in a range of $15k to $75k) and happiness (rated on a scale of 1 to 10) in an imaginary sample of 500 people. The income values are divided by 10,000 to make the income data match the scale of the happiness scores (so a value of $2 represents $20,000, $3 is $30,000, etc.)
# Getting started in R
Start by downloading R and RStudio. Then open RStudio and click on File > New File > R Script.
# Importing all libraries required in this notebook
>import pandas as pd<br>
import numpy as np <br> 
import matplotlib.pyplot as plt <br> 
%matplotlib inline<br>
# Reading data from remote link
>url = "http://bit.ly/w-data"<br>
s_data = pd.read_csv(url)<br>
print("Data imported successfully")<br>
s_data.head(10)<br>

Data imported successfully <br>
![image](https://user-images.githubusercontent.com/97663851/157607826-4980f617-dd72-4333-8019-04a56967eb43.png)

