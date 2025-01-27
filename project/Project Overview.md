# Let's Start with Pandas

Pandas is a high-level manipulation and analysis library that is heavily used in python. it provides data structures such as Series and DataFrames which makes working with structured data more convenient. This document describes some important functions and graph types in Pandas.
# PROJECT:
- ### First we take a unique data set from
-  ### [Kaggle](https://www.kaggle.com)
-  ### My data set is about weather prediction
- ### Download a dataset as a .csv file and link with a jupitor notebook and do following steps: 
- Data Load 🔄
- Data Preprocessing 🛠  
-  Data Cleaning 🧹
- Data Aggregation 🌱  
- Data Save 💾

### Table of content
- ### Data Loading
- [head()](#head)
- [tail()](#tail)
- [info()](#info)
- [describe()](#describe)
- [sample()](#sample)
- ### Data Preprocessing
- [loc()](#loc)
- [iloc](#iloc)
- [new column](#new-column)
- ### Data Cleaning
- [drop()](#drop)
- [dropna()](#dropna)
- [fillna()](#fillna)
- [replace()](#replace)
- [rename()](#rename)
- ### Data Aggregation
- [groupby()](#groupby)
- [isnull()](#isnull)
- [mean,mode,median](#mean,mode,median)
- [count()](#count)
- [sum()](#sum)
- ### Graphs
- [Graph Types in Pandas](#graph-types-in-pandas)

- ### head()
    
The head() function gives the user the first n rows in a DataFrame.
 By default, it returns first five rows.

- ### tail()



The tail() function returns the final n rows in a DataFrame.
 By default, it returns last five rows.

- ### info()
Provides a concise summary of the DataFrame, including the number of non-null entries, column types, and memory usage. 

- ### describe()


The describe() function creates the summary descriptive statistics
 of the DataFrame which includes count, mean, standard deviation, minimum, maximum, and etc.

- ### sample()


The sample() function gives back an arbitrary sample 
of items from a particular axis of the Data Frame.

- ### loc[]
The ‘loc’ indexer allows selection of multiple rows
 and columns using labels or a boolean array.

- ### iloc

The ‘iloc’ indexer allows selection of multiple rows
 and columns by using the integer position.

- ### drop() 
  
Removes rows or columns by specifying labels or index positions.
 - ### dropna() 
  
Removes rows or columns containing NaN values.
 - ### fillna() 
  
Fills missing (NaN) values with a specified value or method 
- ### groupby()

The groupby() function is primarily used to separate the data
into different groups using a certaincriterion and is very 
often followed by an aggregation function.

- ### isnull()

The isnull() function is used to identify and locate
any missing values in the DataFrame.

- ### rename()

The rename() function is used to modify the names 
of the DataFrame columns.

- ### mean, median, mode

Pandas help us find the mean, median and mode
of the DataFrame using functions.

- ### count()

The count() function in pandas is used to count the non-NA/null values in a DataFrame or Series along a specified axis (rows or columns). 

- ### sum()

The sum() function in pandas calculates the sum of values 
along a specified axis (rows or columns) of a DataFrame or Series.

- ### value_counts()
The value_counts() function in pandas is used to count  
 the occurrences of unique values  in a pandas Series or DataFrame column

- ### new column
to add a new column 
df['col1] = 5(value)

- ### All rows and columns
  to display all rows and columns of data we use  
  pd.set_option("display.max_rows",None)
pd.set_option("display.max_columns",None)  
df


# Graph Types in Pandas


- ### Line Graph

A line graph is a type of graph in which information is represented
 by way of a series of markers connected with a straight line.


- ### Bar Graph

A bar graph is a type of graph that uses rectangular bars 
to show comparisons between categorical data.

-  ### Horizontal Bar Graph

A horizontal bar graph is a type of graph that is similar
 to a bar graph but the bars are shown horizontally.

- ### Box Plot

A box plot is a method of showing data dispersion based
 on the five-number summary.

- ### Scatter Plot

A scatter plot is used to show the relationship between
 two numerical variables.

- ### Area Plot

An area plot is used to represent cumulative totals over time.

- ### Pie Chart

A pie chart is used to show the proportions of a whole.

