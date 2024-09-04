# Pandas

Pandas are used for data analysis and manipulation.

Features:
1. Analyse and Manipulate daya
2. Columns can be inserted or deleted
3. Group rows/columns of a dataframe/series
4. Plotting is possible
5. Fix inaccurate data
6. Clean data
7. Handle duplicates
8. Handle missing data NaN,NA,NAT

**Pandas Dataframe:** two dimensional table with rows and columns
Parameters:
1. data
2. index
3. columns
4. dtype
5. copy

loc vs iloc : loc is used to access data by index values and iloc is used to access a group of rows or columns by integers

Methods:
1. dtypes
2. ndim
3. size
4. shape
5. index
6. T
7. head()
8. tail()

join() - method which joins 2 dataframes
df1.join(df2)

concat() - Concatenate the content of data frames
pd.concat([df1,df2])

**Series** - One dimensional array like a column in a table
Parameters:
1. data
2. index
3. dtype
4. name
5. copy

Methods:
1. dtype
2. ndim
3. size
4. name
5. hasnans
6. index
7. head()
8. tail()
9. info()

combine() - method to combine 2 series

1. Create categorical series in pandas (dtype='category')
2. Create categorical dataframe in pandas

Insert cols
df.insert(1,'Section',['a','b','c','d','e'])
print(df)

Insert cols at last
df2=df.assign(rollno=[101,102,103,104,105])
print(df2)

drop columns
df2=df2.drop(columns=['Section'])
print(df2)

drop rows
df2=df2.drop(labels=[3,4],axis=0)
print(df2)


Iterate rows
1. iterrows()
2. itertuples()

Sort values
df2=df2.sort_values(by='Marks',ascending=True)
print(df2)

Find duplicates:
duplicated()
drop_duplicates()

Clean the data
1. isnull()
2. notnull()
3. df.dropna()
4. df.fillna(x)

String Operations
1. lower()
2. upper()
3. title()
4. len()
5. count()
6. contain()

remove whitespaces and characters
1. strip()
2. lstrip()
3. rstrip()




