# Pandas - Python Data Analysis Library

Pandas is a powerful open-source library for data manipulation and analysis in Python. It provides data structures such as **Series** and **DataFrame**, which make handling structured data easy and efficient.

## Installation

To install Pandas, use the following command:
```sh
pip install pandas
```

## Key Features
- **Data Structures:** `Series` (1D) and `DataFrame` (2D tables)
- **Data Manipulation:** Filtering, sorting, and grouping
- **Handling Missing Data:** Methods for handling NaN values
- **File I/O:** Read and write data from CSV, Excel, JSON, SQL, and more
- **Integration:** Works well with NumPy, Matplotlib, and other libraries

## Basic Usage

### Importing Pandas
```python
import pandas as pd
```

### Creating a DataFrame
```python
data = {'Name': ['Alice', 'Bob', 'Charlie'], 'Age': [25, 30, 35]}
df = pd.DataFrame(data)
print(df)
```

### Reading Data from a CSV File
```python
df = pd.read_csv('data.csv')
print(df.head())
```

### Writing Data to a CSV File
```python
df.to_csv('output.csv', index=False)
```

### Handling Missing Data
```python
df.fillna(value='Unknown', inplace=True)
```

## Learning Resources
- [Pandas Documentation](https://pandas.pydata.org/docs/)

---
This README provides a quick reference for Pandas usage. For detailed guides and tutorials, explore the official documentation and resources!
