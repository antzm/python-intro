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
### Scalars, Vectors, Matrices

* Creating a Scalar *

```python
scalar = np.array(1)
scalar.shape
# ()
```

* Creating a Vector *

```python
vector = np.array([1,2,3])
vector.shape
# (3,)
```

* Creating a Matrix *

```python
matrix = np.array([[1,2,3], [4,5,6], [7,8,9]])
matrix.shape
# (3, 3)
```

### Arrays with random numbers

* Array with random numbers from 0 (inclusive) to 1 (exclusive)

```python
array = np.random.rand(10)
```

* Array with random integrs from min_nun (inclusive) to max_num (exclusive)

```python
min_num = 1
max_num = 100
arr_size = 10

array = np.random.randint(min_num, max_num, size)
```
