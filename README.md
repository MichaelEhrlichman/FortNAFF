# FortNAFF
Numerical Analysis of Fundamental Frequencies (NAFF) Algorithm implemented in Fortran 90.

This is an implementation of J. Laskar's NAFF algorithm in Fortran 90.  This code was originally developed for the Bmad particle accelerator simulation library.

At present, this code is dependent on the numerical recipes module "nr" that is distributed with Bmad.  The numerical recipes modules used are brent, which is a root finder, and four1, a fast fourier transform.
These nr modules can be obtained from GitHub here: https://github.com/bamford/astrobamf/tree/master/nr/fortran

