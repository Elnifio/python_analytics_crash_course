# Intro Python for Analytics

## Pre-class setup
**Students must have a Python installation and required packages before class.** I won't require you to
have any specific Python distribution; if you can do the following you are ready for class. If you cannot, please
see the section *Package installation*.

Pre-class checklist:
* Open a terminal
* Run `jupyter notebook` (this should open your web browser)
* Create a new notebook (select the Python option)
* In your notebook, type the follwing and press Shift-Enter.

```
import pandas
import sklearn
import matplotlib
```

If that all runs without an error, you are ready for class.

## Package installation
The easiest way to get
this all up and running is to download the [Miniconda](https://docs.conda.io/en/latest/miniconda.html) distribution of Python. Choose **version 3.7**.

Once you have Miniconda installed, we will install the Python analytics packages
we'll need for class. Open a terminal. On OSX, press Command-Enter and type Terminal. On Windows, try any of [these](https://www.isunshare.com/windows-10/4-ways-to-open-command-prompt-in-windows-10.html).

In your terminal window, run
```
conda install pandas scikit-learn matplotlib jupyter
```
This will install the required packages into your Miniconda distribution.

Now in your terminal, run `jupyter notebook`. If this opens a page in your web
browser, and if the installation of the packages didn't have any errors, you
are ready for class.

## Acknowledgements
This material adapted from Lilyanne Zhang's tutorial [here](https://github.com/zhanglilyanne/data-science-crash-course/).
