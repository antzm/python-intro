# NumPy (Numerical Python)

## NumPy Examples

### Import NumPy

```python
import numpy as np
```

### Creating nd arrays

```python
first_array = np.arange(10)
print(first_array)
# array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```

```python
second_array = np.arange(10)
print(second_array)
# array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```

```python
both_arrays = [first_array, second_array]
matrix = np.array(both_array)
print(matrix)
# [[1 2 3 4 5 6 7 8 9]
#  [1 2 3 4 5 6 7 8 9]]
```
