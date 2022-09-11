# Bayesian-Digressions

## MCMC

- PyMC [installation](https://github.com/pymc-devs/pymc/issues/4937)
  - create file `environment_pymc.yml` with the following content:
  
    ```yml 
    name: env4pymc
    channels:
      - conda-forge
      - defaults
    dependencies:
      - libpython
      - blas
      - mkl-service
      - m2w64-toolchain
      - numba
      - pip
      - python=3.8
      - python-graphviz
      - scipy
      - pip:
        - pymc3
    ```
    
  - run `conda env create -f environment_pymc.yml` 
  - install Jupyter: `pip install jupyterlab`
  - reinstall Numpy and Xarray:
    - `pip install --upgrade numpy==1.20.3`
    - `pip install xarray==0.20.2`
  - see [Post Installation Checks - Do Not Skip This Step on Windows](https://github.com/pymc-devs/pymc/issues/4937) (or [saved as PDF](https://github.com/jsdiazpo/Bayesian-Digressions/blob/master/PyMC3%20installation%20post%20checks.pdf))
  
### Examples

- [Fitting a Model to Data](http://dfm.io/emcee/current/user/line/#) (emcee)
- [A Beginner's Guide to Markov-Chain Monte Carlo (MCMC)](https://prappleizer.github.io/Tutorials/MCMC/MCMC_Tutorial_Solution.html)

## Tutorials
 add...           
