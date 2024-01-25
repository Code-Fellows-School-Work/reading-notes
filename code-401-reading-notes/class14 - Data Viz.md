# Class 14 - Data Visualization

## [Matplotlib Tutorial](https://github.com/rougier/matplotlib-tutorial)

- Repo containing tutorial on Matplotlib
- Matplotlib is a low-level, versatile plotting library
- Provides a wide array of basic plotting functions and is highly customizable

## [Seaborn Tutorial](https://www.activestate.com/resources/quick-reads/how-to-run-linear-regressions-in-python-scikit-learn/)

- Built on top of Matplotlib, Seaborn is a high-level interface for drawing attractive and informative statistical graphics
- It simplifies the process of creating complex visualizations

## [Bokeh Tutorial](https://mybinder.org/v2/gh/bokeh/bokeh-notebooks/master?filepath=tutorial%2F00%20-%20Introduction%20and%20Setup.ipynb)

- Bokeh is a library that specializes in creating interactive and scalable web-based visualizations. It can handle large datasets and dynamic data

## Additional Resources

[Seaborn Cheat Sheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf)

### Questions

1. What are the key differences between Matplotlib, Seaborn, and Bokeh libraries in terms of their features and use cases? Provide an example of a specific visualization that is more suitable for each library
- Matplotlib: low-level library with basic plotting functions. Used for simple viz like bar and line charts
- Seaborn: built on top of Matplotlib, a high-level interface for informational graphics. Used for satistical viz like a heat map
- Bokeh: creates interactive plots and dashboards using real-time data. Used for vizs that require interaction like a interactive scatter plots

2. In the Seaborn library, what are the main functions to create relational, categorical, and distribution plots? Briefly explain the purpose of each type of plot and provide an example use case.
- ```replot()```: visualize relationship between two variables like a scatter plot or line plot and an example measuring the relationship between happiness index vs hours worked from home
- ```catplot()```: visualize a variable that is categorial like a box plot and an example is measuring the median price of a home in various San Diego neighboorhoods
- ```displot()``` and ```histplot```: visualize distribution of a data set to help understand underlying patterns and tendencies like a histogram and an example is distribution of customer ages that buy an android phone

3. Discuss the role of the Seaborn Cheat Sheet in a Python developer’s workflow. What are some key sections or elements featured in the cheat sheet that can help a developer quickly reference Seaborn functionalities?
- The cheat sheet outlines a developer's workfrom from importing the data to visualizing the data. Key sections are (1) import libraries and (3) the requirements for each type of plot

## Things I want to know more about

- Are these the only three libraries that are used for data viz or are there more?
- How does a data scientist determine what type of viz to use? Is it based on customer requirements or data scientist's best judgement to determine the most effective method to draw conclusions from?