title_meta : DATA SCIENCE
<br/>
title      : NumPy,Pandas and Matplotlib Packages
<br/>
description : Data science deals with the manipulation of data
<br/>
NumPy is a Python package to efficiently do data science. Learn to work with the NumPy array, a faster and more powerful alternative to the list, and take your first steps in data exploration.
<br/>
pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
<br/>
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.


<h1>Data-Science<h1/>

<h2>Variable Assignment<h2/>
<h3>Create a variable savings<h3/>

savings = 100

<h3>Print out savings<h3/>
print(savings)

#Replace list elements
<h3>Create the areas list<h3/>
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

<h3>Correct the bathroom area<h3/>
areas[-1] = 10.50

<h3>Change "living room" to "chill zone"<h3/>
areas[4] = "chill zone"

<h2>Import package<h2/>
<h3>Definition of radius<h3/>
r = 0.43

<h3>Import the math package. Now you can access the constant pi with math.pi.<h3/>
import math

<h3>Calculate the circumference of the circle and store it in C<h3/>
C = 2 * math.pi * r

<h3>Calculate the area of the circle and store it in A.<h3/>
A = math.pi * r**2

<h2>Import numpy<h2/>
import numpy as np

<h3>Create Numpy array np_height, that is equal to first column of np_baseball.<h3/>
np_height = np_baseball[:,0]
print(np_height)

<h3>Print out the mean of np_height<h3/>
print(np.mean(np_height))

<h3>Print out the median of np_height<h3/>
print(np.median(np_height))

<h3>Basic scatter plot, log scale<h3/>
plt.scatter(gdp_cap, life_exp)
plt.xscale('log') 

<h3>The strings xlab and ylab variables.<h3/>
xlab = 'GDP per Capita [in USD]'
ylab = 'Life Expectancy [in years]'
title = 'World Development in 2007'

<h3>Use these variables to set the label of the x- and y-axis.<h3/>
plt.xlabel(xlab)
plt.ylabel(ylab)
#plt.title(title)


<h3>Add title<h3/>
plt.title(title)

<h3>After customizing, display the plot<h3/>
plt.show()

<h3>To import CSV files, you still need the pandas package: import it as pd<h3/>
import pandas as pd

<h3>Use pd.read_csv() to import cars.csv data as a DataFrame.<h3/> 
#Store this dataframe as cars
cars = pd.read_csv("cars.csv")

<h3>Print out cars<h3/>
print(cars)
