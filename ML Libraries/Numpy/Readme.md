## NumPy:

* NumPy stands for Numerical Python.
* NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
* NumPy is a Python library and is written partially in Python, but most of the parts that require fast computation are written in C or C++.

### Why do we use Numpy?
* In Python we have lists that serve the purpose of arrays, but they are slow to process.
   * NumPy arrays are stored at one continuous place in memory unlike lists, so processes can access and manipulate them very efficiently.
   * This behavior is called locality of reference in computer science.
   * This is the main reason why NumPy is faster than lists. Also it is optimized to work with latest CPU architectures.

* NumPy aims to provide an array object that is up to 50x faster than traditional Python lists.
* The array object in NumPy is called *ndarray*, it provides a lot of supporting functions that make working with *ndarray* very easy.
