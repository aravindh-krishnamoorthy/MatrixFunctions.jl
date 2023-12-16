# MatrixFunctions.jl
A Julia package for computing scalar and matrix-valued functions of matrix variables and their Fréchet derivatives

_**Note:** This package is still under development. The features with check marks below are available. Those without are to be developed._

## Reading Progress [1]
- ~~Chapter {1,4,9,13}/{1,4,9,13}~~

## Matrix-valued Functions of Matrix Variables
- Matrix function `fm(f, X)`
    - [X]  `fm_schur_parlett_recurrence(f, X)` File: [schur_parlett.jl](https://github.com/aravindh-krishnamoorthy/MatrixFunctions.jl/blob/main/src/schurr_parlett.jl)
    - [ ] ⚡ `fm_schur_parlett_block(f, X)` File: [schur_parlett.jl](https://github.com/aravindh-krishnamoorthy/MatrixFunctions.jl/blob/main/src/schurr_parlett.jl)
    - [ ] ...
- [ ] Matrix polynomial `pm(p, X)`

# Fréchet derivatives
- [ ] Matrix polynomial and its Fréchet derivative `pm_frechet(f, X, E)`
- [ ] Matrix function and its Fréchet derivative `fm_frechet(f, X, E)`

# References
| | |
| --- | --- |
| [1] | Higham, Nicholas J. Functions of matrices: theory and computation. Society for Industrial and Applied Mathematics, 2008. |

# Notes
- From https://github.com/JuliaLang/julia/discussions/43982#discussioncomment-6678802
  -  The block method given above (Eq 3.16)
  -  Daleckii-Krein using the eigendecomposition for normal matrices (Corollary 3.12)
  -  Using the Schur decomposition, if you know the Frechet derivative of f(T) for triangular T (Problem 3.2)
