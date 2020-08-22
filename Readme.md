# Company Valuation With Python

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

## Notebooks

Each Notebook covers a different Section within the article ...

| No. | Section No. | Valuation Type | Notebook |
|-----|-------------|----------------|----------|
| 1   | 4.1.        | DFE            | [Discounted Future Earnings](https://github.com/sankhaMukherjee/theMarketDuringCOVID/blob/master/Download%20-%20List%20of%20companies%20in%20the%20SNP500.ipynb)
| 2   | 4.2.        | DCF            | 
| 3   | 4.3.        | P/S            | 
| 4   | 4.4.        | P/E            | 


## Others

If you encounter any problem, please create an issue using the issue tracker.
I shall attempt to address them as best as possible.

