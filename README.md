# MatrixFunctions.jl
A Julia package for computing scalar and matrix-valued functions of matrix variables and their Fréchet derivatives
**Note:** This package is still under development. The features with check marks below are available. Those without are to be developed.

## Reading Progress [1]
- ⚡Chapter 1/14

## Matrix-valued Functions of Matrix Variables
- [ ] `matrix_function(f, X)`
  - [ ] Diagonal matrices
  - [ ] Symmetric/Hermitian matrices
  - [ ] Arbitrary Matrices
        
- [ ] `matrix_function_frechet(f, X, E)`
  - From https://github.com/JuliaLang/julia/discussions/43982#discussioncomment-6678802
  - [ ] The block method given above (Eq 3.16)
  - [ ] Daleckii-Krein using the eigendecomposition for normal matrices (Corollary 3.12)
  - [ ] Using the Schur decomposition, if you know the Frechet derivative of f(T) for triangular T (Problem 3.2)

# References
| | |
| --- | --- |
| [1] | Higham, Nicholas J. Functions of matrices: theory and computation. Society for Industrial and Applied Mathematics, 2008. |
