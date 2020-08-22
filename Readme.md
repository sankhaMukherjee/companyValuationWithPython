# Company Valuation With Python

# theMarketDuringCovic

This is a set of Jupyter Notebooks that may be used for
replicating the examples within the Medium article, 
[Company Valuation With Python]().

## Installation

The package requirements have been intentionally kept to a minimal so that the 
Notebooks may be run with minimal effort. Some data files have also been
provided. Packages have not been used unless absolutely necessary. The list
of packages needed for the build are:

1. `numpy` : This is for various numerical tasks
2. `scipy` : This has been used for interpolation
3. `matplotlib` : for all the plotting examples
4. `jupyter` : for the Notebooks of course
5. `financeMacroFactors` : Used for downloading fundamental and other stock data
6. `tqdm` : A simple progress bar

### Installing `financeMacroFactors`

This package is available in the repository:

https://github.com/sankhaMukherjee/financeMacroFactors

You can install this package directly into your current
virtual environment with the command:

`pip3 install git+https://github.com/sankhaMukherjee/financeMacroFactors.git`

## General Order of Running the Notebooks

It is preferable to go through the Notebooks in the following order:

1. [Download - List of companies in the SNP500](https://github.com/sankhaMukherjee/theMarketDuringCOVID/blob/master/Download%20-%20List%20of%20companies%20in%20the%20SNP500.ipynb)
2. [Download - Fundamental data for SNP500 companies](https://github.com/sankhaMukherjee/theMarketDuringCOVID/blob/master/Download%20-%20Fundamental%20data%20for%20SNP500%20companies.ipynb)
3. [Download - Stock Data form Yahoo Finance](https://github.com/sankhaMukherjee/theMarketDuringCOVID/blob/master/Download%20-%20Stock%20Data%20form%20Yahoo%20Finance.ipynb)
4. [The Market During Covid](https://github.com/sankhaMukherjee/theMarketDuringCOVID/blob/master/The%20Market%20During%20Covid.ipynb)

## Others

If you encounter any problem, please create an issue using the issue tracker.
I shall attempt to address them as best as possible.

