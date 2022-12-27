# Data-Analysis-with-Python-Census-Dataset
It is a project of Data Analysis with Python or you can say, Data Science with Python on the "India Census" Data set.


The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
style.hide_index( ) - To hide the index of the dataframe.
style.set_caption('Description of the dataframe') - To give a caption to the dataframe.
isin( ) - To show all records including particular elements.
groupby(‘Col_1’)[‘Col_2’] .sum( )[‘value’] - GroupBy – Two Keys – Apply on Col_2 grouped by Col_1.
df[df.Col_1 == 'Element1']['Col_2'] - Filtering - Filter the records of the dataframe wrt to Element1 of Col1 and then showing results of Col2 only.
set_index( ‘Col_Name’ ) - To set any column of a DF as an index.
add_prefix(‘value_’) - To add prefix to the column name.
add_suffix(‘_value’) - To add suffix to the column name.

.......................................................................

Q. 1) How will you hide the indexes of the dataframe.
Q. 2) How can we set the caption / heading on the dataframe.
Q. 3) Show the records related with the districts - New Delhi , Lucknow , Jaipur.
Q. 4) Calculate state-wise :
A. Total number of population.
B. Total no. of the population with different religions.
Q. 5) How many Male Workers were there in Maharashtra state ?
Q. 6) How to set a column as index of the dataframe ?
Q. 7a) Add a Suffix to the column names.
Q. 7b) Add a Prefix to the column names.
