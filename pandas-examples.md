# Pandas Examples

## Import libraries

```python
import numpy as np
import pandas as pd
```

## Pandas Series

```python
# Create a Pandas Series from an numpy array
array = np.arange(5)
pandas_series = pd.Series(array)
```

```python
# Add labels
labels = ['first', 'second', 'third', 'fourth', 'fifth']
new_pandas_series = pd.Series(array, labels)
```
## Pandas DataFrames

```python
array = np.arrange(30)         # creating an np array from 0 to 29
matrix = array.reshape(5,6)    # reshaping the array to a 5x6 matrix (note that 5*6=30)
row_labels = 'R1 R2 R3 R4 R5'.split()        # splitting the row names to R1, R2 etc.)
column_labels = 'C1 C2 C3 C4 C5 C6'.split()  # splitting the column names to C1, C2 etc.) 
data_frame = pd.DataFrame(matrix, row_labels, column_labels) # Creating the DatFrame
data_frame
```
## Adding columns to a DataFrame

```python
# Adding a new column that contains the sum of all the columns
data_frame['column_sum'] = df['C1']+df['C2']+df['C3']+df['C4']+df['C5']+df['C6']
```
## Removing a column from a DataFrame

```python
data_frame.drop('column_sum',axis=1,inplace=True)
# axis=1 refers to columns, while axis=0 refers to rows
# inplace=True removes the original column
# inplace=False retains the original column
```

## Conditional Selection from a DataFrame

**Example 1**

```python
# Keeps only the items of the data frame which are greater than 10
# The rest of the items, are replaced with NaN values
data_frame[data_frame > 10]
```

**Example 2**
```python
# Keeps only the items of the data frame which are are not equal to 10
# The items thar are equal to 10, are replaced with NaN values
data_frame[data_frame != 10]
```