### Array Creation Methods

```numpy.arange```
  - Return evenly spaced values within a given interval. Values are generated within the half-open interval (start, stop) (in other words, the interval including start but excluding stop). For integer arguments the function is equivalent to the Python built-in range function, but returns an ndarray rather than a list.

```numpy.zeros```
  - Return a new array of given shape and type, filled with zeros.

```numpy.ones```
  - Return a new array of given shape and type, filled with ones.

```numpy.linspace```
  - Return evenly spaced numbers over a specified interval.
  - Returns num evenly spaced samples, calculated over the interval (start, stop).
  - The endpoint of the interval can optionally be excluded.

```numpy.eye```
  - Return a 2-D array with ones on the diagonal and zeros elsewhere.

```numpy.random.rand```
  - Random values in a given shape.
  - This is going to populate an array of the given shape you pass in and it's going to populate it with random samples from a uniform distribution over 0 to 1.

```numpy.random.randn```
  - Return a sample (or samples) from the “standard normal” distribution.

```numpy.random.randint```
  - Return random integers from low (inclusive) to high (exclusive).
  - Return random integers from the “discrete uniform” distribution of the specified dtype in the “half-open” interval (low, high). If high is None (the default), then results are from (0, low).
