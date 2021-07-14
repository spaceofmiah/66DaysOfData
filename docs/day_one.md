# Day 1 

I learnt about reshaping and resizing of ndarray. There are couple of ways methods provided by NumPy for reshaping an array. Today i identified well with

- **np.reshape**: This changes the shape of an ndarray e.g

```python
arr_1 = np.arange(1, 13)    # would generate a one dimensional array from 1 through 12 

# [1, 2, 3, ....., 12]

arr_1.reshape(1, 1, 3, 4) # would create a view with a 2 dimensional array having 3r & 4c

# [
#   [
#       [1,  2,  3,  4]
#       [5,  6,  7,  8]
#       [9, 10, 11, 12]
#   ]   
# ]
```

- **np.ravel**: changes a multi-dimensional array to a one dimensional array

- **np.expand_dims**: adds a new axis to an ndarray. Has same functionality as np.newaxis