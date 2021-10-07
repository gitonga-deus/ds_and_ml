### NumPy also has its own builtin generation methods of creating arrays

```numpy.arange``` 
  - numpy.arange *([start, ]stop, [step, ]dtype=None, like=None)*
  - Return evenly spaced values within a given interval. Values are generated within the half-open interval (start, stop) (in other words, the interval including start but excluding stop). For integer arguments the function is equivalent to the Python built-in range function, but returns an ndarray rather than a list.

```numpy.zeros``` - Return a new array of given shape and type, filled with zeros.

```numpy.ones``` - Return a new array of given shape and type, filled with ones.

```numpy.linspace``` - numpy.linspace(start, stop, num=50, endpoint=True, retstep=False, dtype=None, axis=0)

```numpy.eye``` - this is an identity matrix.

```numpy.random.rand``` - this is going to populate an array of the given shape you pass in and it's going to populate it with random samples from a uniform distribution over 0 to 1.

```numpy.random.randn``` - returns random numbers from a standard normal distribution centered around 0.

```numpy.random.randint``` - returns random integers from a low to a high number and also a size
