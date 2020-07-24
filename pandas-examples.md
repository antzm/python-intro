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
