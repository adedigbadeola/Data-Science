<h1>Data-Science<h1/>
<h2>NumPy,Pandas and Matplotlib Packages<h2/>
<br/>
<h4>Description : Data science deals with the manipulation of data
<br/>
NumPy is a Python package to efficiently do data science. Learn to work with the NumPy array, a faster and more powerful alternative to the list, and take your first steps in data exploration.
<br/>
pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
<br/>
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.<h4/>

<h2>Variable Assignment<h2/>
<h3>Create a variable savings<h3/>
<h6>savings = 100<h6/>
<h3>Print out savings<h3/>
<h6>print(savings)<h6/>

<h3>Create the areas list<h3/>
<h6>areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]<h6/>

<h3>Correct the bathroom area<h3/>
<h6>areas[-1] = 10.50<h6/>

<h3>Change "living room" to "chill zone"<h3/>
<h6>areas[4] = "chill zone"<h6/>

<h2>Import math package<h2/>
  
<h3>Definition of radius<h3/>
<h6>r = 0.43<h6/>

<h3>Import the math package. Now you can access the constant pi with math.pi.<h3/>
<h6>import math<h6/>

<h3>Calculate the circumference of the circle and store it in C<h3/>
<h6>C = 2 * math.pi * r<h6/>

<h3>Calculate the area of the circle and store it in A.<h3/>
<h6>A = math.pi * r**2<h6/>

<h2>Import numpy<h2/>
<h6>import numpy as np<h6/>

<h3>Create Numpy array np_height, that is equal to first column of np_baseball.<h3/>
<h6>np_height = np_baseball[:,0]<h6/>
<h6>print(np_height)<h6/>

<h3>Print out the mean of np_height<h3/>
<h6>print(np.mean(np_height))<h6/>

<h3>Print out the median of np_height<h3/>
<h6>print(np.median(np_height))<h6/>

<h2>The matplotlib package<h2/>
<h3>Basic scatter plot, log scale<h3/>
<h6>plt.scatter(gdp_cap, life_exp)<h6/>
<h6>plt.xscale('log')<h6/> 

<h3>The strings xlab and ylab variables.<h3/>
<h6>xlab = 'GDP per Capita [in USD]'<h6/>
<h6>ylab = 'Life Expectancy [in years]'<h6/>
<h6>title = 'World Development in 2007'<h6/>

<h3>Use these variables to set the label of the x- and y-axis.<h3/>
<h6>plt.xlabel(xlab)<h6/>
<h6>plt.ylabel(ylab)<h6/>
  
<h3>Add title<h3/>
<h6>plt.title(title)<h6/>

<h3>After customizing, display the plot<h3/>
<h6>plt.show()<h6/>

<Import pandas<h2/>
<h3>To import CSV files, you still need the pandas package: import it as pd<h3/>
<h6>import pandas as pd<h6/>

<h3>Use pd.read_csv() to import cars.csv data as a DataFrame.<h3/> 
<h4>Store this dataframe as cars<h4/>
<h6>cars = pd.read_csv("cars.csv")<h6/>

<h3>Print out cars<h3/>
<h6>print(cars)<h6/>
