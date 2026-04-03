Experiment No. 11: Creation and Loading of Dataset using Pandas

Aim:

To create a dataset manually and to load and analyze an external dataset using the Pandas library in Python.

Objectives:

1.To understand the concept of structured data.

2.To create a DataFrame using a Python dictionary.

3.To load a dataset from a CSV file.

4.To perform basic data analysis operations using Pandas.

Theory:

Pandas is an open-source Python library widely used for data analysis and manipulation. It provides powerful data structures such as Series (1D) and DataFrame (2D), which allow efficient handling of structured data.

A dataset can be created manually using Python data structures like dictionaries or lists, and can also be imported from external sources such as CSV files. Pandas provides several built-in functions to explore, clean, and analyze the dataset, such as:

1.head() and tail() to view data

2.info() to get structural details

3.describe() for statistical summary

4.isnull() to detect missing values

Procedure:

1.Import the required libraries (pandas, numpy).

2.Create a dataset using a Python dictionary.

3.Convert the dictionary into a Pandas DataFrame.

4.Display dataset dimensions using shape and size.

5.Analyze the dataset using:

5.1.info() for structure

5.2.describe() for statistics

6.Load an external dataset using read_csv().

7.Perform operations:

7.1.Display first and last records (head(), tail())

7.2.Get random samples (sample())

7.3.Check missing values (isnull().sum())

7.4.Check duplicate records (duplicated().sum())

7.5.Count unique values (nunique())

Observations:

1.The manually created dataset contains structured student data.

2.The external dataset (Cars93) contains multiple attributes related to cars.

3.Some columns may contain missing values.

4.Statistical summary provides insights such as mean, standard deviation, etc.

Result:

The dataset was successfully created using a dictionary and converted into a DataFrame. The external dataset was also loaded and analyzed using various Pandas functions.

Conclusion:

Pandas is an efficient and user-friendly library for handling datasets. It allows easy creation, loading, and analysis of structured data, making it a powerful tool for data science and data analysis tasks.
