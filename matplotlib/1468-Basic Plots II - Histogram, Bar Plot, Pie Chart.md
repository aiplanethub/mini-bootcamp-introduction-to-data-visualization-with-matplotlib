# Histogram

### What is Histogram?

A histogram is a graphical display of data using bars(rectangles) of different heights.

**Parts of a Histogram:**

* **The title:** The title describes the information included in the histogram.
* **X-axis:** The X-axis are intervals that show the scale of values which the measurements fall under. These intervals are also called bins.
* **Y-axis:** The Y-axis shows the number of times that the values occurred(frequency) for each interval on the X-axis.
* **The bars:** The height of the bar shows the number of times that the values occurred within the interval, while the width of the bar shows the interval that is covered.



### **Example: Height of Orange Trees**

* You measure the height of every tree in the orchard in centimeters (cm)
* The heights vary from 100 cm to 340 cm
* You decide to put the results into groups of 50 cm:
  * The 100 to just below 150 cm range,
  * The 150 to just below 200 cm range, Etc…
* So a tree that is 260 cm tall is added to the "250-300" range.











![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d5d586fd4a2e47daa555be899b531aca.png)














* **And here is the result:**






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2f22bdd00d5341adb508d41986111197.png)






* You can see (for example) that there are 30 trees from 150 cm to just below 200 cm tall. You just created a histogram!
* Source: https://www.mathsisfun.com/data/histograms.html



### Creating a Histogram

Matplotlib can be used to create histograms using the hist() method.

**Parameters:**

* x(n,) : this takes either a single array or a sequence of arrays which are not required to be of the same length.
* bins : intervals of any quantity

If the bins are:

[1, 2, 3, 4]

then the first bin is [1, 2) (including 1, but excluding 2) and the second [2, 3). The last bin, however, is [3, 4], which includes 4.






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_63e97e1cab1547bbb0ac9e72357fb840.png)






### **Applications of Histogram**

* Histograms are a very common type of plots when we are looking at data like height and weight, stock prices, waiting time for a customer, etc which are continuous in nature.
* Histograms are good for showing general distributional features of dataset variables. You can see roughly where the peaks of the distribution are, whether the distribution is skewed or symmetric, and if there are any outliers.

# Bar Plot

### What is Bar Plot?

Bar charts are one of the most common types of graphs and are used to show data associated with categorical variables.

Let's see some ways to display a bar graph with matplotlib:






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f6582cfb0ad94fa8bbd6c1a5caa48686.png)





### Creating a Vertical Bar Plot

Pyplot provides a bar() method to make bar graphs which take the following arguments: categorical variables, their values and color (if you want to specify any). 








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_21c6bb192e6b4cd2b42179ac53b0dfd9.png)










### Creating a Horizontal Bar Plot

It’s also really simple to make a horizontal bar-chart using the plot.barh() method.









![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_5f02309e817b4caeacc3515946d57b14.png)








### Bar Charts with multiple quantities

When comparing several quantities and when changing one variable, we might want a bar chart where we have bars of one color for one quantity value.

We can plot multiple bar charts by playing with the thickness and the positions of the bars.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_ac9c91b9bdaa488ea6670e133440dedc.png)





### Stacked Bar Charts 

The stacked bar chart stacks bars that represent different groups on top of each other. The height of the resulting bar shows the combined result of the groups.






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f2cfb1391fc7464a925f36ba15e8b6a7.png)





### Applications of Bar Charts 

Bar graphs are used to match things between different groups or to trace changes over time. Look at the bar chart below representing the most in-demand tech skills for data engineers.







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_7efdb65711b44d47b19cf579b6519c62.png)







### Bar Chart vs Histogram

Histograms are a great way to show results of continuous data, such as:

* weight
* height
* how much time etc.

But when the data is in categories (such as Country or Favorite Movie), we should use a Bar Chart. Have a look at the next part descripting the difference between histogram and bar chart:








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2f1be5631f5242b8bc28e05a1e66fd3f.png)








# Pie Chart

### What is Pie Chart?

* A pie chart (or a circle chart) is a circular statistical graphic, which is divided into slices(wedges) to illustrate numerical proportion.

* Imagine a pizza where different slices contain different toppings. Bigger the slice, larger the amount of that topping is present.








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_22c4c086041540838c428ed1ed0bd044.png)







### **Parameters of a pie chart:**

* x: The wedge sizes.
* labels: A sequence of strings providing the labels for each wedge.
* Colors: A sequence of colors through which the pie chart will cycle. If None, will use the colors in the currently active cycle.
* Autopct: string, used to label the wedges with their numeric value. The label will be placed inside the wedge. The format string will be fmt%pct.

We can also pass in arguments to customize our Pie chart to show shadow, explode a part of it, tilt it at an angle or do lot more exciting things!

**Don’t get overwhelmed with the terms being used, it’ll be all clear in the below section.**

### **Creating a Pie Chart**

Pie chart can be made using the method pie().




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c0b0e09c28364ca8a7ea866745736123.png)





### **Applications of Pie Charts**

* A pie chart is best used when trying to work out the composition of something. If you have categorical data then using a pie chart would work really well as each slice can represent a different category. A good example of a pie chart can be seen below.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_08352ad4b0414f1da1e11e3839c5be69.png)





* Another good use for a pie chart would be to compare areas of growth within a business such as turnover, profit and exposure.
* Try creating a pie chart to see how much money you spend in different areas.