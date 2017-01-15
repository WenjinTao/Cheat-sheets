### Expand dimension

X_train.shape
- ([], 32, 32)

> np.expand_dims(X_train, axis=3)

X_train.shape
- ([], 32, 32, 1)

### [Repeat element](https://docs.scipy.org/doc/numpy/reference/generated/numpy.repeat.html)

> x = np.array([[1,2],[3,4]])

> np.repeat(x, 2)

array([1, 1, 2, 2, 3, 3, 4, 4])



