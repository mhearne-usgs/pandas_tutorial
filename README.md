# Python Plotting 
This repository contains the tutorial "Pandas Tutorial " which is part of the 2021 GHSC HazDev Summer Python Tutorial Series.

Please use Binder via the link below to launch this tutorial in your web browser:

https://hub.gke2.mybinder.org/user/mhearne-usgs-pandas_tutorial-0vp44hj4/notebooks/pandas_tutorial.ipynb

If you prefer to run the notebook locally, clone the repository:

`git clone git@github.com:mhearne-usgs/pandas_tutorial.git`

 and run the following commands in the top level of the repository:

(on Mac or Linux)
- `bash install.sh`

on Windows:
- `conda create -n plotting_tutorial python>=3.6 jupyter ipython matplotlib numpy cartopy pandas -y`
- `conda activate pandas_tutorial`
- `jupyter notebook pandas_tutorial.ipynb`

\*Note: Anaconda or Miniconda must be installed first

- https://docs.anaconda.com/anaconda/install/
- https://docs.conda.io/en/latest/miniconda.html

## The topics covered include:
 - Defining Data
 - Loading Data
 - Examining Data
 - Selecting Data
    - Series Object
    - Series Data
    - Index Definition
    - Selecting Data by Column
    - Selecting Data by Row
 - Create Significant Events
    - Removing Missing Data
    - Select Rows by Multiple Criteria
 - Saving Results
 - Plotting Results
 - Working with String Data
 - Applying Functions to Data
 - Resources
