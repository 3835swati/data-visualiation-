# DATA-VISUALIZATION-
In this project , we are given number of items sold on respective date in respective place #Insights from the visualizations

1.the total units of rescpective description

2.the total units in respctive month

#what else can we visualize:

1.the unit of descriptions sold in respective place on respective date

#What was done:

we imported pandas library which is used to analyze data
in second line , we got the overview of data
then we used head to read first 50 rows
then describe is used to return the description of data
info is used to get the information about the data
we created a new varibale df2 in which we use groupby to get the relation between description and unit
fillna(0) is used to replace null values with 0
As the unit was in float so to plot bar chart we will convert it into int.
now we imported matplotlib library which is used to visualize and plot many graphs
we plotted bar chart of description vs unit
imported regex which is used to extract month from date in this data
In new variable df1 , return the data of month and unit
used groupby to find relation between month and unit
converted it into int to plot graph
pot bar graph of month vs unit to see in which month the sale is more i.e.. april with 68 units sold

#Libraries used:

Pandas
Matplotlib
Regex
