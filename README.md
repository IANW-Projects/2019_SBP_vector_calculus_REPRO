# Discrete Vector Calculus and Helmholtz Hodge Decomposition for Classical Finite Difference Summation by Parts Operators

[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/203920739.svg)](https://zenodo.org/badge/latestdoi/203920739)

This repository contains some code used in the following article
which is available on [arXiv](https://arxiv.org/abs/1908.08732).
```
@article{ranocha2020discrete,
  title={Discrete Vector Calculus and {H}elmholtz {H}odge Decomposition
         for Classical Finite Difference Summation by Parts Operators},
  author={Ranocha, Hendrik and Ostaszewski, Katharina and Heinisch, Philip},
  journal={Communications on Applied Mathematics and Computation},
  volume={2},
  pages={581--611},
  year={2020},
  month={02},
  eprint={1908.08732},
  eprinttype={arxiv},
  eprintclass={math.NA},
  doi={10.1007/s42967-019-00057-2}
}
```

If you find these results useful, please cite the article mentioned above.
If you use the implementations provided here, please cite this repository as
```
@misc{ranocha2019discreteRepro,
  title={{2019\_SBP\_vector\_calculus\_REPRO}.
         {D}iscrete Vector Calculus and {H}elmholtz {H}odge Decomposition for
         Classical Finite Difference Summation by Parts Operators},
  author={Ranocha, Hendrik and Ostaszewski, Katharina and Heinisch, Philip},
  year={2019},
  month={08},
  howpublished={\url{https://github.com/IANW-Projects/2019_SBP_vector_calculus_REPRO}}
}
```

## Brief Description

This repository contains two [Jupyter](https://jupyter.org/) notebooks
containing [Julia](https://julialang.org/) code.
- `notebooks/grid_oscillations__used.ipynb`
  Here, grid oscillations associated to nullspace consistent
  first derivative summation by parts (SBP) operators are visualised.
  The corresponding figures in the article can be reproduced using
  this code and interactive experiments are set up.
- `notebooks/projections__used.ipynb`
  Here, a discrete Helmholtz Hodge decomposition using classical
  finite difference SBP operators is conducted for several parameters.
  Besides visualisations of the decomposition in two and three space
  dimensions, convergence studies and applications to wave mode
  analysis of the magnetohydrodynamic (MHD) equations are presented.
  This notebook contains the code for all other numerical examples
  and figures in the article.


## Disclaimer

Everything is provided as is and without warranty. Use at your own risk!
