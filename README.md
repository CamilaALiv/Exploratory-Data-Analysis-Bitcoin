# Exploratory Data Analysis (EDA)

Exploratory data analysis (EDA) is an important step in the data analysis process that aims to explore and better understand the data before applying more advanced modeling techniques. In Python, there are several libraries that can be used for EDA, such as Pandas, Matplotlib, and Seaborn.

Below, I will provide an example of EDA using the Pandas library, which is widely used for data manipulation and analysis.
We will use a dataset containing information about Bitcoin Prices from 2014 until 2023. This dataset is available at https://www.kaggle.com/datasets/kapturovalexander/bitcoin-and-other-14-most-significant-cryptos

The CSV file with the data can be read in Python as follows:

![1](https://user-images.githubusercontent.com/123582788/233453421-49441d69-4b2f-40f2-a4ff-837d14fae198.png)

Now, let's explore some EDA techniques to better understand the data.
## 1. Checking the data structure:
We can use the **head()** method to view the first few rows of the dataset and check the structure of the data.

![2](https://user-images.githubusercontent.com/123582788/233453642-e1597d26-f90a-45fa-95d6-e95d66e346fd.png)

## 2. Checking basic statistics:
We can use the **describe()** method to obtain basic statistical information about the data, such as mean, standard deviation, minimum, maximum, and quartiles.

![3](https://user-images.githubusercontent.com/123582788/233454020-6576b47d-8940-4493-9ef4-6b5a89123e9b.png)

## 3. Checking for missing values:
We can use the **isnull()** method to check if there are any missing values in the dataset.

![4](https://user-images.githubusercontent.com/123582788/233454168-2f14b328-7262-41c3-afb2-b6ea71bced9b.png)

We can see that in this dataset we have no missing values. 

## 4. Checking the distribution of data:
We can use a histogram to check the distribution of data in a particular column.

![5](https://user-images.githubusercontent.com/123582788/233454441-abdc3bbd-0912-440e-8900-4f50716f0520.png)

## 5. Checking the relationship between variables:
We can use a scatter plot to check the relationship between two variables.

![6](https://user-images.githubusercontent.com/123582788/233454529-9a75aff5-201b-4d7c-b69d-88ecf0de9828.png)

These are just a few examples of EDA techniques in Python. Through the use of other libraries and methods, it is possible to further explore the data and obtain important information for the analysis process.

![2222](https://user-images.githubusercontent.com/123582788/233456281-3fc96245-62e7-4eed-9d91-2c5e20f02f0d.png)
