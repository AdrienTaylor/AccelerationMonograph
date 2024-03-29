# Acceleration Monograph

This code can be used to verify the theoretical statements from the monograph

> [1] Alexandre d’Aspremont, Damien Scieur and Adrien Taylor (2021), "Acceleration Methods", Foundations and Trends® in Optimization: Vol. 5: No. 1-2, pp 1-245.


The arXiv version is available [**here**](https://arxiv.org/abs/2101.09545), the Foundation and Trends version is available [**here**](https://www.nowpublishers.com/article/Details/OPT-036).

#### Authors

- [**Alexandre d'Aspremont**](https://www.di.ens.fr/~aspremon/)
- [**Damien Scieur**](https://damienscieur.com/)
- [**Adrien Taylor**](adrientaylor.github.io/)

**Notes:**
- Files in the folders [`Proofs of Chapter 4/01_Symbolic`](Proofs_of_Chapter_4/01_Symbolic) and [`Proofs of Chapter 5/01_Symbolic`](Proofs_of_Chapter_5/01_Symbolic) require Mathematica (for verifying analytical developments).
- Files in the folders  [`Proofs of Chapter 4/02_Numerical`](Proofs_of_Chapter_4/02_Numerical) and [`Proofs of Chapter 5/02_Numerical`](Proofs_of_Chapter_5/02_Numerical) require [YALMIP](https://yalmip.github.io/) along with a suitable SDP solver (e.g., Sedumi, SDPT3, Mosek), and the Performance Estimation Toolbox ([PESTO](https://github.com/AdrienTaylor/Performance-Estimation-Toolbox)).
- Files in the folders [`Proofs of Appendix C/`](Proofs_of_Appendix_C/) require Mathematica (for verifying analytical developments and performing the numerical experiments).

## Content

### (Accelerated) Gradient Methods (Chapter 4)

[`Proofs of Chapter 4`](Proofs_of_Chapter_4/) contains two subfolders.
- [`01_Symbolic`](Proofs_of_Chapter_4/01_Symbolic/) contains Mathematica notebooks for verifying the algebraic manipulations required in the proof of the potential inequalities for the 14 gradient methods in this chapter.
- [`02_Numerical`](Proofs_of_Chapter_4/02_Numerical/) contains Matlab codes for verifying the final bounds of the methods presented in the chapter.


### (Accelerated) Proximal Methods (Chapter 5)

[`Proofs of Chapter 5`](Proofs_of_Chapter_5/) contains two subfolders.
- [`01_Symbolic`](Proofs_of_Chapter_5/01_Symbolic/) contains Mathematica notebooks for verifying the algebraic manipulations required in the proof of the potential inequalities for the 4 proximal methods in this chapter.
- [`02_Numerical`](Proofs_of_Chapter_5/02_Numerical/) contains Matlab codes for verifying the final bounds of the 4 proximal methods presented in the chapter.

### On Worst-case Analyses for First-order Methods (Appendix C)

[`Proofs of Appendix C/`](Proofs_of_Appendix_C/) contains Mathematica notebooks for obtaining (analytically) and solving (numerically) the LMI formulations from Appendix C.
