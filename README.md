# Gaussian Distribution Package
Python package for Binomial and Gaussian distribution.


## Table of Contents
1. [Project Motivation](###project-motivation)
2. [Licensing, Authors, and Acknowledgements](###licensing,-authors,-and-acknowledgements)
3. [Installation](###Installation)
4. [Usage](###Usage)
5. [Licensing and Acknowledgements](###Licensing-and-Acknowledgements)



### Project Motivation
Start contributing to the python pypi package. The package computes the Binomial and Gaussian for list of numbers.

### Installation
The following libraries meke the dependencies for the package
* Python3
* matplotlib
Installation of the package is available [here](https://pypi.org/project/udnd-probability/)

```
pip install udnd-probability

```

### Usage
The package provides means of calculating mean, standard deviation, probability density functions of Binomial and Gaussian distributions

Example:
```
binomial = Binomial(0.4, 20)
binomial.read_data_file('numbers_binomial.txt')
mean = binomial.calculate_mean() # calculates the mean

# Adding two distributions
gaussian_1 = Gaussian(25, 2) # takes mean and stdev
gaussian_2 = Gaussian(20, 3)
result = gaussian_1 + gaussian_1 
```

### Licensing and Acknowledgements
Credit is due to Udacity Data Scientist NanoDegree Program!