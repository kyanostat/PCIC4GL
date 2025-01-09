# PCIC4GL

(Written by Keisuke Yano; 20250109)

This page provides python codes for Posterior Covariance Information Criterion developed in the following paper:

==========================================================================

Paper information: https://arxiv.org/abs/2312.09586

Title: Posterior covariance information criterion for general loss functions

Authors: Yukito Iba (The Institute of Statistical Mathematics), Keisuke Yano (The Institute of Statistical Mathematics)

Abstract: 

==========================================================================


## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)

## Introduction
We develop a novel generalisation error estimate that accommodates general evaluation and score functions in line with generalized Bayesian computation.
The proposed method employs the posterior covariance to provide bias correction for empirical errors and presents an asymptotically unbiased estimator for generalisation errors.


## Requirements
- Python 3.x
- Libraries:
  - `numpy`
  - `pymc>=5.9`
  - `numpyro`
  - `pypolyagamma 1.2.3`
  - `psis` from https://github.com/avehtari/PSIS


## Usage
1. **Run the Jupyter Notebook:**
   
   Open the provided notebook `PCIC_v1.ipynb` using Jupyter Notebook:
    ```bash
    jupyter notebook PCIC_v1.ipynb
    ```
   Follow the steps in the notebook to reproduce the results.

2. **Use the Functions in Scripts:**
   
   If you want to use the code in standalone Python scripts, refer to the key functions outlined in the notebook. You can import these functions into your own code as needed.
