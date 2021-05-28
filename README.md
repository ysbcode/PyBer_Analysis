# PyBer_Analysis
Using Python, Matplotlib, Pyplot, Pandas and Jupyter Notebook to perform analysis on PyBer ride sharing data.

## Overview of the Analysis

**To perform this project, we used Python to code the analysis we want to perform. In addition to used two open-source packages within Python called Pandas, Numpy and Matplotlib to assist with the analysis and visualize the results. Finally we used the computational noebook Jupyter Notebook to write, edit and manipulate our code for Python.** 

In this project, we were provided with two data sets from the Company Pyber: Individual ride data and data by city. We merged these two data to create a comprehensive data set. Using this data set and the original indivdual data sets, we were asked to perform two types of analysis:
 - Calculate and present Average Fare data by ride and by driver indexed by type of city
 - Present Pyber fares by type of city spread over a four(4) month period 

## Results and Analysis

The image below shows the average fare per ride and average fare per driver for the three types of cities where Pyber operate. 

![](https://github.com/ysbcode/PyBer_Analysis/blob/main/analysis/Summary_dataframe.png?raw=true)

As the results show, the urban cities generate significanly larger amount of revenue than rural and suburban cities. This is in line with our expectations as urban areas have a higher population and thus greater demand for Pyber. The average fare per ride and per driver is lowest in urban areas which again is in line with our expectations since urban areas tend to have small distances from point A to B and high concentration of drivers which leads to smaller fares per ride and per driver. 

The image below shows the distribution of Pyber income spread over a four (4) month period. 

![](https://github.com/ysbcode/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png?raw=true)

The revenue distribution over the four(4) month period is interesting. Both urban and suburban areas have a gradual increase in total fares from January to mid february. After that, both these cities have irregular distribution of fares. The second point of interest is that all three types of cities have a peak in fares in the third week of February which I believe require further investigation. 

## Summary

We have listed three recomendations to the CEO based on our observations of the data.
 - The Company should look to add drivers during the period Feb 15 to March 01 because that seems to be a peak period
 - Fares in urban areas seem to decrease after April 15 while fares in suburban areas appear to increase in the same period. The Company should look to divert drivers from urban areas to suburban areas during this period. 
 - Since rural areas have the highest average fares, the Company could expand in rural areas as they might have higher growth potential. 
