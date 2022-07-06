# Setting Things Up

### Learning Objectives

* Importing Libraries
* About the Dataset
* Loading the dataset

### Importing libraries

All Python capabilities are not loaded to our working environment by default (even if they are already installed in your system). So, we import each and every library that we want to use.

We’ll import numpy, pandas and matplotlib with their respective aliases: **np, pd and plt.**






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_4cbfb8081ca44de7b679b1f58e5a9144.png)






### About the Dataset

**Dataset Name:** Standard Metropolitan Dataset

**Dataset Description:**

* It contains data of 99 standard metropolitan areas in the US i.e. 99 row entries.
* The dataset provides information on 11 variables for each area for the period 1976-1977.
* The areas have been divided into 4 geographic regions: 1=North-East, 2=North-Central, 3=South, 4=West.
* The variables provided are listed in the table below:








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_0ffc57b6c31f48ff800b37f81f0cd107.png)






### Objective

The problem objective is to find the crime rate of each area.

### Loading the dataset

For loading the dataset, we’ll use the Pandas **read_csv** method.

Here's the CSV of the dataset: [Standard Metropolitan Areas Dataset](https://raw.githubusercontent.com/dphi-official/Datasets/master/Standard_Metropolitan_Areas_Data-data.csv)

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_7ffa3304d85343ae8fba3b9acff4d605.png)