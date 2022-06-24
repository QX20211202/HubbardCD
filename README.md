# HubbardCD

This code generates the data reported in arXiv:2206.07597 http://arxiv.org/abs/2206.07597

Variational counterdiabatic protocol for 1D Hubbard chain up to $L = 14$ sites with $l \leqslant 3$.

Sparse matrices are explicitly stored in the memory. For the extreme case $L = 14$ and $l = 3$, the sparse matrix needs more than 333 GB memory.

Time evolution is solved by using Chebyshev polynomial expansion.

Exterme eigenvalues are calculated using Lanczos algorithm.

