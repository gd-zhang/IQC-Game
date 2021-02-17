## Introduction
This repository contains the code to reproduce the IQC results from the paper [A Unified Analysis of First-Order Methods for
Smooth Games via Integral Quadratic Constraints](https://arxiv.org/pdf/2009.11359.pdf).

## Requirements
We used [CVXPY](https://www.cvxpy.org/) package along with MOSEK solver in the paper. 

To install CVXPY and MOSEK:
```
pip install cvxpy
pip install mosek
```

 - Note that you will need the MOSEK license. You can request a free [academic license](https://www.mosek.com/products/academic-licenses/) if you are a student or faculty. For license issues, please check the instruction [here](https://docs.mosek.com/9.2/licensing/index.html).
 - You could also use other installed solvers in CVXPY, however the results would be quite different. We found that MOSEK solver is stable numerically and runs faster than other packages. 


## Citation
To cite this work, please use
```
@article{zhang2020unified,
  title={A Unified Analysis of First-Order Methods for Smooth Games via Integral Quadratic Constraints},
  author={Zhang, Guodong and Bao, Xuchao and Lessard, Laurent and Grosse, Roger},
  journal={arXiv preprint arXiv:2009.11359},
  year={2020}
}
```
