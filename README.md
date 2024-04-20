# Python Fundamental for Data Analyst Part 2

Welcome to "Python Fundamentals for Data Analyst Part 2"!🐍

Here, you will find a variety of materials and code examples designed to deepen your understanding of the Python fundamentals that are essential to becoming a competent data analyst.
Various topics have been prepared from learning about using functions, utilizing the NumPy library, processing data using Pandas, Random, Datetime, and Txt Files (Open, Read, Close).

We hope that the materials we present can help you develop your data analysis skills using Python. 

Thank you for your visit!🙌

## Function
* In mathematics, a function is a process that relates an input to an output.
* In Python, besides being a relation function, a function is also a way to organize code - with the ultimate goal of reusable code.
* Functions are best when they have a specific purpose but can be reused.
* Python provides common functions.
* However, we can always define our own functions.

### Definition a Function:
* Functions are defined using the keyword def followed by the function name and its parameters enclosed in parentheses ().
* Optionally, you can add a docstring - a documentation string that explains the function's context.
* The code block within each function starts with a colon and uses indentation.
* A function terminates when there is a return statement [expression] that returns [expression] to the caller.
* You can also create functions that do not return output by using return none."

<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/c37e18da-916f-487d-b4df-3c0691ee6b62" /></div>

### Calling a Function
By default, python will position each parameter according to the registration order in which they were defined, and must be called in accordance with that order
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/af439b12-fdf5-4d2d-8312-552659240d70" /></div>

### Return Statement
The return [expression] statement will make program execution exit the current function, while returning a certain value.
* The return value of a function can be stored in a variable.
* This will differentiate a function that returns a value from a function that does not return a value (often called a procedure)
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/a60c83bd-7958-49f8-a696-bf7b469f1c93" /></div>

### Pass by Reference vs Value
* All parameters (arguments) in the Python language are "passed by reference". This means that when we change a variable, the data that references it will also change, both inside the function and outside the calling function.
* Unless we perform an assignment operation that will change the reference parameter

<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/18646bbc-3ef3-430a-b6a7-f58ef2c5ed55" /></div>
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/75f78874-1989-41d3-8123-c48e98f0b2e8" /></div>

# **NumPy**
NumPy is a Python library used for **working with arrays**. It also has functions for working in domain of linear algebra, fourier transform, and matrice.

> Import NumPy
> 
> syntax: import numpy as np

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/2d40ad2b-645b-4c29-a821-e4fec8a5d1e3" /></div>

### Make a NumPy Array 
<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/70053701-085f-4821-a167-dab4d024e303" /></div>

### Make a NumPy with Tuple
<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/8ec120a7-4a04-4f9f-9858-a2651b70c673" /></div>

## Dimension
Dimensions are groups of attributes based on columns from tables or views in a data source view.

1. 0 Dimension

* syntax: a = np.array()
<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/e8aa8aab-bf0b-4af2-b515-2092d29d05b9" /></div>

2. 1 Dimension
<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/470f2b05-35c3-4746-b19c-5bf2f699f0cc" /></div>

3. 2 Dimension
<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/fa0b4392-8334-461e-a32f-9e9044446286" /></div>

4. 3 Dimension
<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/34289dbc-3557-4362-bd82-66d34937a34b" /></div>


### Check Dimension
For check dimension you can use ndim
> syntax: print(arr.ndim)

<div align="center"><img src="https://github.com/salsanssp/Python-for-Data-Analyst-part-2/assets/166114037/72a96572-a4e7-4baa-9642-d2bbcab91282" /></div>

# Pandas Library
Pandas is well-suited for working with tabular data, such as spreadsheets or SQL tables.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/42a0604f-0173-4dd4-bec7-0a954f50a3bd" /></div>

# Data Structures in Pandas Library
Pandas generally provide two data structures for manipulating data. They are:
* Series
* DataFrame
## 1. Pandas Series
A Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, Python objects, etc.). The axis labels are collectively called indexes.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/241f5066-6e3b-4ea3-b637-2d9d0f4e7e76" /></div>
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/5b699c6d-225a-4ab5-b069-6e5c4c8f836d" /></div>
Pandas Series index attribute is used to get or set the index labels of the given Series object.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/8627ece0-fb23-4504-9559-67112e3a73a6" /></div>
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/cb95450a-833b-4161-9950-c95bb87de0db" /></div>

### Create a Series with a random explicit string index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/32c51435-74d9-460b-89cd-3ba87626ba55" /></div>

Pandas Series index attribute is used to get or set the index labels of the given Series object.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/6ed94be6-cafb-4039-907f-23c67cc36955" /></div>

Indexing makes use of explicit index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/352efef0-3f59-470d-9557-383c075d48ca" /></div>

On the other hand, in Pandas, the term 'implicit index' refers to the default index that Pandas assigns to each element in a Series or DataFrame when no explicit index is provided.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/6bd96bfa-e19e-47d6-823f-4a60d3d6d424" /></div>
## loc and iloc
let's creating a sample dataset with matching implicit and explicit indices.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/79af5350-6290-44b2-886c-a3bc08c6faa6" /></div>
To clarify data retrieval, we can use the loc and iloc attributes.

### loc
The loc attribute allows indexing and slicing that always references the explicit index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/70e4fc9c-8bea-4ebe-9668-17b9231a841c" /></div>

### iloc
The iloc attribute allows indexing and slicing that always refer to the implicit integer index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/21035509-cd4c-4ae2-8c4f-2a1e4b643e70" /></div>

## DataFrame
Which was introduced in Python via the Pandas library, is a tabular data structure allowing users to handle and store data in a two-dimensional table structure consisting of rows and columns. It can be interpreted as a set of one or more series, with at least one series included.

Example: Create a DataFrame with 2 Series
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/c4166121-b317-4d09-8248-844cbb832b67" /></div>
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/9462fa52-2c02-4430-9c96-c0c2cd4efbec" /></div>

**Note** : Pay attention when writing the DataFrame. 'D' and 'F' must be capitalized.

### Call Index on Data Frame
Calling an index on a DataFrame typically refers to accessing the index labels or values of rows in a pandas DataFrame in Python or can also data slicing.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/fdf40eeb-10ac-4db1-b1a8-b5d7008a2cd6" /></div>

Additionally, you can use these labels or values to access specific rows in a DataFrame using the .loc[] or .iloc[] method. For example:
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/5d672413-f874-42ab-be46-75fc9ed7bdda" /></div>

## Load CSV Dataset
To load a CSV dataset in Python, you typically use the pandas library, which provides a simple and powerful data manipulation and analysis toolset. But dont forget to make sure place the dataset in same folder with the notebook.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/b456d5fb-7e61-4647-88fb-8855c10d6d6c" /></div>

For example, have the titanic.csv dataset and want to load the dataset:
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/d80075c6-df55-4e5f-ab0e-363d02dcb019" /></div>

### Head()
The head() returns the first n rows for the object based on position. If your object has the right type of data in it, it is useful for quick testing. This method is used for returning top n (by default value 5) rows of a data frame or series.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/d4731936-d173-4a14-8c77-a9095e95945f" /></div>

### Info()
Provides a concise summary of a dataframe. It displays information about the dataframe, including the number of rows and columns, the data types of the columns, the number of non-null values in each column, and the amount of memory used by the dataframe.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/2f8dda11-0add-479c-88df-742834c6066e" /></div>

### Sum() with notnull and isnull
The sum() method adds all values in each column and returns the sum for each column. By specifying the column axis ( axis='columns' ), the sum() method searches column-wise and returns the sum of each row.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/0d04e996-8adc-45a8-bd97-2f028e8e2795" /></div>

### Tail()
Returns last n rows from the object based on position. It is useful for quickly verifying data, for example, after sorting or appending rows. Number of rows to select.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/beca0775-4f34-4827-b20e-faa797133195" /></div>

### Shape()
Provides information about the number of rows and columns in a DataFrame quickly and easily.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/15698c76-c381-4e1b-8e78-b88bf85b0e21" /></div>
In the Titanic dataset, there are 891 rows and 12 columns

### Column()
Returns a list of column labels from a DataFrame. This makes it possible to find out the names of the columns in the DataFrame.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/5c26835d-f92a-4258-b0bb-1a56112c7cac" /></div>

### Index()
Provides information about the index labels of the DataFrame.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/da00821e-54b2-41bf-9d9b-ce1c6611a250" /></div>

### Describe()
Generates summary descriptive statistics from the DataFrame, which includes some general statistics about the numeric columns in the DataFrame
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/6fe05c8f-ebfc-4528-a975-d1ef2845c506" /></div>

### Mean
Calculates the average of the values in a DataFrame. It is the sum of all values divided by the total number of values.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/caa36161-8810-4d7b-8d48-e9748cc0b087" /></div>

### Median
Calculates the median of the values in a DataFrame. Median is the middle value in a sequence of data when the data is sorted.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/6c85e55c-57ff-4a38-ab22-b1665eae9deb" /></div>

### Mode
Calculates the mode of the values in a DataFrame. The mode is the value that appears most frequently in the dataset.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/c3f5f18e-cbd8-4427-91d9-6b06ef984fbc" /></div>

### Min and Max
* Min(), Returns the minimum value in a DataFrame.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/2ce78616-7c07-4ae2-be8b-0dfa42029921" /></div>

* Max(), Returns the maximum value in a DataFrame.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/431885ec-ee0c-48f3-8de9-df0b765595b1" /></div>

### Mask
Replace values where the condition is True.
<div align="center"><img src="https://github.com/Vanz92x/Python-Fundamental-for-Data-Analyst-2/assets/165736197/3402ca70-0f1d-4caa-a821-26118556d172" /></div>

### Calculate the sum of values
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/4e73c1d7-0894-4352-addb-0fd140aadf41" /></div>

### Unique and Nunique
`Unique` and `Nunique` in the context of Python refer more to the presence of repeating or non-repeating elements in a data structure, and how to identify and manipulate those elements.
- Unique (non-repetitive)
To get the unique elements of a data structure like list, we can use set(). Set is a data structure that contains only unique elements
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/b0135ff9-e9cc-4349-a71e-24b984b17c5a" /></div>

- Nunique (Repetitive or Duplicate) 
To get repeated or duplicate elements from a data structure, we can use various approaches, for example by using certain functions or modules, or by manually looping through the data structure.
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/ff0ce817-24bf-472f-a7c6-9779fe2c425d" /></div>

### Call a specific column
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/941512de-9504-40b8-ac31-08deeb345a34" /></div>
                        
As another example You can use less than `<`, more than `>`, less than equal to `<=`, not equal to `!=`. Customize the data type with the function to be used. You can also call by combining the data types used in one line. 

<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/8920f699-2b2a-4f9e-91e5-f0bc1eb886fe" /></div>

## Random library
Random library in Python is used for generating random numbers. It provides various functions for generating random integers, selecting random elements from a list, shuffling sequences, and more.
 you can use this Syntax : 
 `import random
    print(random.random())`

- Generate Random Numbers in Python
random.randint() method is used to generate random integers between the given range.
`Syntax: randint(start, end)`

<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/d76b9e1a-4716-4cc3-81d0-11023142313b" /></div>
 

- Python random.sample() function is used to return a random item from a list, tuple, or string.
  `Syntax: random.sample(sequence, length)`

<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/a71a951c-b023-4478-9cc0-bc424cf4b927" /></div>
 
## Open, Read and Close File TXT
- Open
To open the file, use the built-in open() function. The open() function returns a file object, which has a read() method for reading the content of the file.
`Example Syntax : workfile = open ('stok.txt' , 'r')` 
  
- Read
  In the code snippet above, we read the content of the file using the read() method.

# Python Journey🐍
Thank you for joining the Python Fundamentals for Data Analyst Part 2 adventure! We hope the materials we've provided inspire and enrich your knowledge in data analysis using Python. Stay enthusiastic in exploring the world of data, and don't hesitate to share your discoveries with the community. See you on the next journey! 🌟

















