# Stabilized Barzilai-Borwein Step Size
MATLAB MEX implementation of SVRG-SBB algorithms

This code replicates the experiments from the following paper:

- ["Global Linear Convergence of Stochastic Variance Reduced Gradient in Stochastic Semidefinite Optimization".<br> Jinshan Zeng, Ke Ma, Yuan Yao.](https://arxiv.org/abs/1711.06446)

Please cite this paper if you use this code in your published research project.

## Requirement
In MATLAB:
``` 
>>mex -v -g -largeArrayDims *.c
```
and run the script with the mex function, data file in the same directory.
