# Class 12 - Pandas

## [Pandas in 10](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

- Series: a one-dimensional labeled array holding data of any type
    - ex. ```s = pd.Series([1, 3, 5, np.nan, 6, 8])```
- DataFrame: a two-dimensional data structure that holds data like a two dimensional array
    - ex. ```dates = pd.date_range("20130101", periods=6)```
    - ```df.head()``` displays the header of the data structure
    - ```df.tail()``` displays the footer of the data structure

## [What is Pandas](https://www.youtube.com/watch?v=dcqPhpY7tWk&t=391s)

- Youtube tutorial demonstrating capabilities of pandas library to include manipulating and transforming data and data visualization

## Additional Resources

[Pandas Tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/index.html)
[Pandas Youtube Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS)
[Master Pandas](https://towardsdatascience.com/be-a-more-efficient-data-scientist-today-master-pandas-with-this-guide-ea362d27386)

### Questions

1. Explain the purpose and basic functionality of the Pandas library. What are some common operations that can be performed on data using Pandas, and how do they contribute to data analysis and manipulation?

- Handles series of dataframe data structures and can create, view, select, transform, manipulate and visualize data. The library includes tools commonly used within the data science industry to analyze and manipulate data.

2. What are the primary data structures in Pandas, and how do they differ in terms of use cases?

- Series: a one-dimensional labeled array holding data of any type
- DataFrame: a two-dimensional data structure that holds data like a two dimensional array
- A series is similar to the properties of an array in JavaScript and lists in Python whereas a DataFrame is similar to an excel spreadsheet

3. Describe the process of loading a dataset into a Pandas DataFrame. What are some common file formats that can be used, and which Pandas functions are utilized to read these formats?

- Use specific read functions functions depending on the file format.
- Common file formats are CSV, parquet and excel
- ```read.csv(), read.parquet, read.excel```

## Things I want to know more about
- Why is it called pandas?