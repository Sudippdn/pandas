# pandas
Pandas in a python's library that has functions for analyzing, cleaning, exploring, and manipulating data.

## How to import pandas in Jupyter nootbook or any other IDE?
To import pandas library, you just need to type this code:
```python
import pandas as pd
```

## How to import files or data in pandas?

There are basically two ways to insert data for manipulation in pandas. They are:
1. Excel Files
2. CSV files (commas-separated-values)

## 1. Excel files
  Both excel files read the dataset in a similar manner and the pandas can read the excel file by the following command:
  ```python
DataFrame = pandas.read_excel("FileName.excel")
```
```python
DataFrame = pandas.read_excel(r"FilePath.excel")
```

## 2. CSV files (comma separated values)
  Both excel files read the dataset in a similar manner and the pandas can read the excel file by the following command:
  ```python
DataFrame = pandas.read_csv("FileName.csv")
```
```python
DataFrame = pandas.read_csv(r"FilePath.csv")
```
