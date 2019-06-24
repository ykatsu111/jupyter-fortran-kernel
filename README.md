# Minimal Fortran kernel for Jupyter

This software is forked from [ZedThree/jupyter-fortran-kernel](https://github.com/ZedThree/jupyter-fortran-kernel) and only a magic command is implimented.

## Manual installation

Make sure you have the following requirements installed:

  * gfortran
  * jupyter
  * python 3
  * pip

Steps to install:

1. `git clone https://github.com/ykatsu111/jupyter-fortran-kernel`
2. `pip3 install --user git+https://github.com/ykatsu111/jupyter-fortran-kernel`
3. `cd jupyter-fortran-kernel`
4. `jupyter kernelspec install --user fortran_spec`

Then, a kernel "Fortran" will be seen in your jupyter notebook or lab.


## Example of notebook

* [Example of notebook (.ipynb)](example-notebook.ipynb)


## Uninstall

1. `jupyter kernelspec uninstall fortran_spec`
2. `pip uninstall jupyter-fortran-kernel`
