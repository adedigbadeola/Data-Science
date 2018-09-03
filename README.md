title_meta  : DATA SCIENCE
title       : NumPy,Pandas and Matplotlib Packages
description : NumPy is a Python package to efficiently do data science. Learn to work with the NumPy array, a faster and more powerful alternative to the list, and take your first steps in data exploration. pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.


# Data-Science

#Variable Assignment
# Create a variable savings
savings = 100

# Print out savings
print(savings)

#Replace list elements
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Correct the bathroom area
areas[-1] = 10.50

# Change "living room" to "chill zone"
areas[4] = "chill zone"

#Import package
# Definition of radius
r = 0.43

# Import the math package. Now you can access the constant pi with math.pi.
import math

# Calculate the circumference of the circle and store it in C
C = 2 * math.pi * r

# Calculate the area of the circle and store it in A.
A = math.pi * r**2

# Import numpy
import numpy as np

# Create Numpy array np_height, that is equal to first column of np_baseball.
np_height = np_baseball[:,0]
print(np_height)

# Print out the mean of np_height
print(np.mean(np_height))

# Print out the median of np_height
print(np.median(np_height))

# Basic scatter plot, log scale
plt.scatter(gdp_cap, life_exp)
plt.xscale('log') 

# The strings xlab and ylab variables. 
xlab = 'GDP per Capita [in USD]'
ylab = 'Life Expectancy [in years]'
title = 'World Development in 2007'

# Use these variables to set the label of the x- and y-axis.
plt.xlabel(xlab)
plt.ylabel(ylab)
#plt.title(title)


# Add title
plt.title(title)

# After customizing, display the plot
plt.show()

# To import CSV files, you still need the pandas package: import it as pd
import pandas as pd

# Use pd.read_csv() to import cars.csv data as a DataFrame. 
#Store this dataframe as cars
cars = pd.read_csv("cars.csv")

# Print out cars
print(cars)
