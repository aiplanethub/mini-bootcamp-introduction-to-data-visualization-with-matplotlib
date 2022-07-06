# Basic Plots

* The terms Plot, Chart and Graph partly overlap, they are used somewhat loosely, and in that overlap there isn't really any significant difference that you need to know right now.
* Therefore, there’s no need to be confused if you find Bar Plot, Bar Graph and Bar Chart being used interchangeably at places.
* Let’s have a look at the commonly used plots in Matplotlib now.







# Scatter Plot

### What is Scatter Plot?

* A scatter plot (aka scatter chart, scatter graph) uses dots to represent values for different numeric variables.
* The position of each dot on the horizontal and vertical axis indicates values for an individual data point.
* Scatter plots are used to observe relationships between variables.









![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_5f5dd9dc082849309f19d4c7542ed3f5.png)








### **Creating a Scatter Plot**

To create a scatter plot in Matplotlib we can use the .scatter() method:







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_eb846dc1ed204e4e8013db2215a9f675.png)






### **Is plt.show( ) always required?**

You might’ve observed the line plt.show( ) after the plt.scatter( ). Is it necessary to use?

* If Matplotlib is used in a terminal, scripts or specialized IDEs such as Spyder, Pycharm or VS Code, plt.show() is a must.
* If Matplotlib is used in an iPython shell or a notebook as Jupyter Notebook or Colab Notebook, plt.show\(\) is usually unnecessary.

The plt.show() command does a lot under the hood, as it must interact with your system's interactive graphical backend. The details of this operation can vary greatly from system to system and even installation to installation, but matplotlib does its best to hide all these details from you.

In the following cell we are executing the same script as above, removing the plt.show() instruction:




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_955a071b23c747ccb9e06a71835cae3e.png)





If you want to prevent this from being included as a cell output, use plt.show() at the end of each plotting instruction.

### **Applications of Scatter Plot**

* A scatter plot can be useful for identifying other patterns in data.
* We can divide data points into groups based on how closely sets of points cluster together.
* Scatter plots can also show if there are any unexpected gaps in the data and if there are any outlier points. (Look at the 2 points away from rest of the data in the scatter plot. Those are outliers.)
* This can be useful if we want to segment the data into different parts, like categorising users into different groups.




# Line Plot

### What is Line Plot?

A line chart is used to represent data over a continuous time span. It is generally used to show trend of a variable over time. Data values are plotted as points that are connected using line segments.

### Creating a Line Plot (with 2 arguments)

* In Matplotlib we can create a line chart by calling the plot method.
* plot() is a versatile command, and can take an arbitrary number of arguments.








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_66da213cfc0e402890a57b7582ce8c48.png)







Because it is a line chart, matplotlib automatically draws a line to connect each pair of consecutive points that represent coordinates on the graph.

### **Creating a Line Plot (with a single argument)**

* We can make a graph with a simple line of code as mentioned in the image:









![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_5498e847bafa4baabed998c816311f1d.png)









* You may be wondering why the x-axis ranges from 0-3 and the y-axis from 1-4.
* If you provide a list of n elements to the .plot() function, matplotlib will assume it is a sequence of  y  values, and automatically generates the  x  values for you as a range of n elements starting from 0. 
* Since python ranges start with 0, the default list x  has the same length as  y . Hence the  x  data will be [0,1,2,3]. (Length same as y(4) but starts from 0 instead).

### Applications of Line Plot

Using a line chart one can see the pattern of any dependent variable over time like share price, weather recordings (like temperature, precipitation or humidity), etc. 

Let's look at an example of the graphical representation of Netflix Paid Subscriber Count growth from 2012 to 2018:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f1729089bc8746e49b8d6744b0c66f07.png)