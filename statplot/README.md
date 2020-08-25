## STATPLOT PACKAGE

Startplot provides expert functionality to quickly calculate Gaussian and Binomial distributions. This package contains Gaussian and Binomial distribution class for calculating Gaussian and Binomial distribution and visualising them.

## Files

The package contains the `setup.py`, `__init__.py`, `Binomialdistribution`, `Gaussiandistribution` and `setup.cfg` files.

The `setup` file contains information about the statplot version development. 

## Installation

To install this package:

` pip install statplot`

And to use it in a python programme: 

- open a python interpreter 
- import statplot using: `from statplot import Gaussian, Binomial`
- If the package is successfully installed, then you can use statplot to calculate your Gaussian and Binomial distributions

for example in the python interpreter the below function will return the mean and stdev of the Gaussian and Binomial distributions of the data

>> Gaussian(10, 7) 

>> Binomial (.4, 25)