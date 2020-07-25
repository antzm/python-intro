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
