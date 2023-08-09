# MatrixFunctions.jl
A Julia package for computing scalar and matrix-valued functions of matrix variables and their Fréchet derivatives

## Reading Progress [1]
- ⚡Chapter 0/14

## ~~Scalar Functions of Matrix Variables~~ (already nicely done by gradient)
- [ ] ~~`scalar_function(f, X)`~~
- [ ] ~~`scalar_function_frechet(f, X)`~~

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
