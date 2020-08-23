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
| 1   | 4.1.        | DFE            | [Discounted Future Earnings](https://github.com/sankhaMukherjee/companyValuationWithPython/blob/master/Discounted%20Future%20Earnings.ipynb)
| 2   | 4.2.        | DCF            | [Discounted Cash Flow](https://github.com/sankhaMukherjee/companyValuationWithPython/blob/master/Discounted%20Cash%20Flow.ipynb)
| 3   | 4.3.        | P/S            | [Price to Sales Ratio](https://github.com/sankhaMukherjee/companyValuationWithPython/blob/master/Price%20to%20Sales%20Ratio.ipynb)
| 4   | 4.4.        | P/E            | [Price to Earnings Ratio](https://github.com/sankhaMukherjee/companyValuationWithPython/blob/master/Price%20to%20Earnings%20Ratio.ipynb)


## Others

If you encounter any problem, please create an issue using the issue tracker.
I shall attempt to address them as best as possible.

