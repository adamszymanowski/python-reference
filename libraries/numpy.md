# Numpy
[NumPy API Reference](https://numpy.org/doc/stable/reference/index.html)

# Routines
[Routines](https://numpy.org/doc/stable/reference/routines.html)

## Array Creation Routines

### From Shape or Value
`numpy.empty()`

Return a new array of given shape and type without initializing entries

`numpy.empty_like()`

Return a new array with the same shape and type as a given array

`numpy.eye()`

Return a 2-D array with ones on the diagonal and zeros elsewhere

`numpy.identity()`

Return the identity array. **The identity array is a square array with ones on the main diagonal and zeros elsewhere.**

`numpy.ones()`

Return a new array of given shape and type, filled with ones

`numpy.ones_like()`

Return an array of zeros with the same shape and type as a given array

`numpy.full()`

Return a new array of given shape and type, filled with `fill_value`

`numpy.full_like()`

Return a full array with the same shape an type as a given array

### From Existing Data
`numpy.array()`

Create an array.

`numpy.asarray()`

Convert the input to an array

`numpy.asanyarray()`

Convert the input to an ndarray, but pass ndarray subclasses through

`numpy.ascontiguousarray()`

Return a contiguous array (ndim >= 1) in memory (C order)

`numpy.asmatrix()`

Interpret input as a matrix

`numpy.copy()`

Return an array copy of given object

`numpy.frombuffer()`

Interpret buffer as 1-dimensional array

`numpy.from_dlpack()`

Create a NumPy array from an object implementig the `__dlpack__` protocol

`numpy.fromfile()`

Construct an array by from data in a text or binay file

`numpy.fromfunction()`

Construct an array by executing a function over each coordinate

`numpy.fromiter()`

Create a new 1-dimensional array from an iterrable

`numpy.fromstring()`

A new 1-D array initialized from text data in a string

`numpy.loadtxt()`

Load data from a text file


### Create record arrays (numpy.rec)
`numpy.rec.array()`

Construct a record array from a wide-variety of objects.

`numpy.rec.fromarrays()`

Create a record array from a flat list of arrays

`numpy.rec.fromrecords()`

Create recarray from a list of records in text form

`numpy.rec.fromstring()`

Create a record array from binary data

`numpy.rec.fromfile()`

Create an array from binary data


### Creating character arrays
`numpy.char.array()`

Create a `chararray`

`numpy.char.asarray()`

Convert input to a `chararray`, copying the data only if necessary


### Numerical ranges
`numpy.arange()`

Return evenly spaced values within a given interval

`numpy.linspace()`

Return evenly spaced numbers over specified interval

`numpy.logspace()`

Return numbers spaced evenly on a log scale

`numpy.geomspace()`

Return numbers spaced evenly on a log scale (a geometric progression)

`numpy.meshgrid()`

Return coordinate matrices from coordinate vectors

`numpy.mgrid`

*nd_grid* instance which returns a dense multi-dimensional "meshgrid"

`numpy.ogrid`

*nd_grid* instance which returns an open multi dimensional "meshgrid"


### Building matrices
`numpy.diag()`

Extract a diagonal or construct a diagonal array

`numpy.diagflat()`

Create a two-dimensional array with the flattened input as a diagonal

`numpy.tri()`

An array with ones at below the given diagonal and zeros elsewhere 

`numpy.tril()`

Lower triangle of an array

`numpy.triu()`

Upper triangle of an array

`numpy.vander()`

Generate a Vandermonde matrix


### The Matrix class
`numpy.mat()`

Interpret the input as a matrix

`numpy.bmat()`

Build a matrix object from a string, nested sequence, or array