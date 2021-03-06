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

* Array with random numbers from 0 (inclusive) to 1 (exclusive) *

```python
array = np.random.rand(10)
```

* Matix 5x5 with random numbers from 0 (inclusive) to 1 (exclusive) *
```python
matrix = np.random.rand(5, 5)
```

* Array with random integrs from min_nun (inclusive) to max_num (exclusive)

```python
min_num = 1
max_num = 100
arr_size = 10

array = np.random.randint(min_num, max_num, size)
```

* Matrix 5x5 with random integrs from min_nun (inclusive) to max_num (exclusive)

```python
min_num = 1
max_num = 100
matrix_size = (5, 5)

matrix = np.random.randint(min_num, max_num, matrix_size)
```

* Array with random numbers [0, 1) that follow the Noraml Distribution *

```python
array = np.random.randn(10)
```

* Matrix 5x5 with random numbers [0, 1) that follow the Noraml Distribution *

```python
array = np.random.randn(5, 5)
```

### Creating special vectors and matrices

**Vector and matrix with zeros**

```python
np.zeros(5)
np.zeros((3,5))
```

**Vector and matrix with ones**

```python
np.ones(5)
np.ones((3,5))
```

**Eye matrix (square)**

```python
np.eye(3)
np.eye(5)
```

### Respaping Matrices

* Creating a vector and reshaping it to various matrices

```python
original_vector = np.arrange(18)
new_matrix = original_vector.respape(3,6)    # note 3*6=18
newer_matrix = original_vector.respape(2,9)  # note 2*9=18
matrix_3d = original_vector.reshape(2,3,3)   # note 2*3*3=18
```

### Matrix calculations

```python
a = np.arange(16).reshape(4,4)
b = np.arangr(16).reshape(4,4)

matrix_sum = a + b
matrix_subtract = a - b
matrix_multiply = a * b
matrix_divide = a / b
```

## Creating arrays and matrices using linspace()

**6 equally distributed values from 1 to 6**

```python
matrix = np.linspace(1, 6, 6)
matrix
```
 
**100 equally distributed values from 1 to 100**

```python
matrix = np.linspace(1,100)
matrix
```