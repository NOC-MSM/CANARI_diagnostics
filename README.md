# CANARI_diagnostics

A public repository for developing and sharing code for diagnosing data from observations and models in the CANARI project (https://ncas.ac.uk/our-science/long-term-collaborations/canari).

This CANARI sub-project code repository, "CANARI_diagnostics" is open to suggested changes (philosophical, structural, stylistic, ...) and was initialised simply to aid collaboration.

Initially, it's likely to be mainly NOC (noc.ac.uk) staff working on the CANARI project who might use it, but others in the CANARI consortium and beyond are also welcome too.

To get started, clone this Git repository, e.g. from the Linux command line : 

`git clone git@github.com:NOC-MSM/CANARI_diagnostics.git`


**Contributors - please add code in either the Python or Fortran directories, accordingly.  Or add a new directory for other types of code.  Also - add at least a one-line description of what your code does, in this README file, below, sorted in alphabetical order.**

e.g. 
FORTRAN/ice_extent.F90 : calculates the area (km^2) based on the sea-ice concentration greater than a threshold value (0.15 default), including non-uniform grid metric terms for the area elements.
FORTRAN/ice_extent.h90 : header file for ice_extent.F90
FORTRAN/grid_define_convert.F90 : general utility module for defining and converting grids, used by other modules (ice_extent.F90, ...)

Python/ice_extent.ipynb : calculates the area (km^2) based on the sea-ice concentration greater than a threshold value (0.15 default), including non-uniform grid metric terms for the area elements.


