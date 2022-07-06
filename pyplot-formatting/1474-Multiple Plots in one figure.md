# Multiple Plots

### Multiple Plots in 1 Figure

* We can make multiple graphics in one figure. This goes very well for comparing charts or for sharing data from several types of charts easily with a single image.

* The .subplot() method is used to add multiple plots in one figure. It takes three arguments:
  * nrows: number of rows in the figure
  * ncols: number of columns in the figure
  * index: index of the plot

* Let's see how variables are plotted with different row and column configurations in the figures.

* The function subplot creates a figure and a set of subplots. It is a wrapper function to make it convenient to create common layouts of subplots, including the enclosing figure object, in a single call.

* You can even give a Title to your subplots using the suptitle method! No, the 'p' is not a typing mistake.

* The subplot function returns a figure and an Axes object or an array of Axes objects.



### Changing Plot Size

If we call the subplot function without any parameters - like we do in the following example - a Figure object and one Axes object will be returned:









![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_926e61763ec748c19e8794e37d62f513.png)








### 1 row and 2 columns - Method 1







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_5a770dbc066b40f1a0b22e0129d6b8dc.png)







### **1 row and 2 columns - Method 2**











![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_8fb6c8493acd4c8cb705fb67558a249e.png)






### Overlapping Values

* Aren't those overlapping axis values annoying? Matplotlib has a solution for that too.

* Simply put sharey=True inside the subplot function. The two subplots will now share the y axis values.

* Try it out!

### 2 rows and 1 column













![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_04ffecf4fd9b4f148b5a4965c26ca176.png)









### 2 rows and 2 columns

Think of this as a 2$\times$2 grid. You can access the different positions of the axis and plot your graphs there as follows:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a8f1a5ce24f84af5940de754b665e961.png)