# HubbardCD

This code generates the data reported in arXiv:XXXX.XXXXX

Variational counterdiabatic protocol for 1D Hubbard chain up to $L = 14$ sites with $l \geqslant 3$.

Sparse matrices are explicited store in the memory. For the extreme case $L = 14$ and $l = 3$, the sparse matrix need more than 333 GB memory.

Time evolution is solved by using Chebyshev polynomial expansion.

Exterme eigenvalues are calculated using Lanczos algorithm.

