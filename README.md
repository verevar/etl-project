# ETL-project


We used 2 different datasets from the public platform Kaggle and wikipedia to find information on natural disasters and the cost per year of those natural disasters. The data in the files included:

*	Year
*	Location
*	Disaster declaration
*	Disaster code
*	Disaster type

The fields of interest include the following:

*	Year
*	State
*	Damage cost of natural disaster
 
 

The following sources for our datasets used:

https://www.kaggle.com/datasets/headsortails/us-natural-disaster-declarations

https://en.wikipedia.org/wiki/List_of_disasters_by_cost


## Transformation 

In order to transform the public data and use it in our study we performed the following:

* Used Pandas functions in Jupyter Notebook to load CSV files.
* Reviewed the files and transformed into data frames
* Created queries to address our hypothesis by grouping the data by state and getting the sum of the number of natural disasters and the cost per year. We sorted the data by state and year.

## Load
The last step was to transfer our final output into a Database. We created a database and respective table to match the columns from the final Panda's Data Frame. 

## Summary

There were some limitations to our findings due to the data available. However, we were able to address our hypothesis question and develop a conclusion that supported the hypothesis.
