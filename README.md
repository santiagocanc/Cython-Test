# Cython vs Python - Performance tests

Python is one of the most used computational tools in the scientific area, due to two factors. Python has a readable structure that allows for a fast development cycle. On the other hand, Python has the ability to use modules in low level environments such as C/C++ and Fortran for accessing internal components.

Since python is an interpreted language, low-level tasks tend to be slow, so resources such as low-level loops are unfeasible. This is why NumPy can help on eliminating the need to use such loops. However, sometimes there are speedups that can't be easily obtained with just Numpy, so using tools like Cython can be of great help

Fundamentally, Cython will compile Python code directly into C, then link it into Python for use. With this, Cython allows to use the execution speed of C in a Python code. We will be using a customized Tester class for ease of use (can be found within the repositories files)


# NN

![Alt Text](https://github.com/AndresTY/randomTemp/blob/main/NN.gif?raw=true )

# PRIMES

![Alt Text](https://upload.wikimedia.org/wikipedia/commons/b/b9/Sieve_of_Eratosthenes_animation.gif)

# POW

![Alt Text](https://github.com/santiagocanc/Cython-Test/blob/main/POW.gif?raw=true)
