## Task 6 Questions:
![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=Python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyterlab-F37626?logo=Jupyter&logoColor=white)

1. Load the necessary package for plotting using pyplot from matplotlib. <br>
   Example - Days(x-axis) represents `8` days and Speed(y-axis) represents a car’s speed. Plot a Basic line plot between days and car speed, put x axis label as days and y axis label as car speed and put title Car Speed Measurement.
   
   ```{python}
       Days=[1,2,3,4,5,6,7,8]
       Speed=[60,62,61,58,56,57,46,63]
   ```
2. Now to above car data apply some string formats  like line style example green dotted line, marker shape like  `+`, change markersize, markerface color etc.
3. Plot Axes Labels, Chart title, Legend, Grid in Car minimum, Maximum and average speed in `8` days.
   ```{python}
       days=[1,2,3,4,5,6,7,8]
       max_speed=[80,91,92,88,77,79,76,75]
       min_speed=[42,43,40,42,33,36,34,35]
       avg_speed=[46,58,57,56,40,42,41,36]
   ```
4. Plotting a basic sine graph by adding more features. Adding Multiple plots by Superimposition like `cosine` wave.
5. Plot Simple bar chart showing popularity of Programming Languages.
    ```{python}
        Languages =['Python', 'SQL', 'Java', 'C++', 'JavaScript']
        Popularity = [56, 39, 34, 34, 29]
        Security = [44 ,36 ,55, 50, 42]
   ```
   Plot Multiple Bars showing Popularity and Security of major Programming Languages. Also Create Horizontal bar chart using `barh` function.
6. Plot Histogram, We have a sample data of Students marks of various Students, we will try to plot number of Students by marks range and try to figure out how many Students are average, below-average and Excellent.
   ```{python}
       Marks = [ 61,86,42,46,73,95,65,78,53,92,55,69,70,49,72,86,64]
   ```

     - Histogram showing Below Average, Average and Execellent distribution.
     - 40-60: Below Average
     - 60-80: Average
     - 80-100: Excellent
7. Titanic Data Set Download Data and Load the data file
     - Create a pie chart presenting the male/female proportion 
     - Create a scatterplot with the Fare paid and the Age, differ the plot color by gender
