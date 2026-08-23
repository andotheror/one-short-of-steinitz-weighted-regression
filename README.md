# One Short of Steinitz: Weighted Regression Selection

## Abstract

How well can least squares perform on a full dataset after training on a small weighted subset? A recent COLT open problem determined the exact worst-case ratio for budgets at most the dimension and at least twice the dimension, leaving every intermediate budget open and reporting an unpublished endpoint argument. We give a complete proof that, for $d$-dimensional homogeneous linear regression and the minimum-norm ERM, the exact ratio with $2d-1$ selected examples is $1+1/d$. The proof identifies the only obstruction to exact recovery one example below the Steinitz threshold. Unless the nonzero full-loss gradients lie on $d$ independent lines and every useful zero-gradient feature is absent, $2d-1$ examples recover the full ERM exactly. On the exceptional cross configuration, the problem splits into one-dimensional regressions and omitting one member of the least-loss line costs at most a $1/d$ fraction of the optimum. A matching construction handles the minimum-norm tie rule. We also give a harmonic lower bound for every intermediate budget and show that it is exact for rank-additive circuit decompositions. This class contains the extremal construction and isolates the remaining obstacle for the full open curve: overlapping positive circuits can only be handled by a new reduction, not by ordinary volume sampling.

## Keywords

weighted regression, data selection, Steinitz lemma, volume sampling, subset selection, harmonic bounds, convex geometry

## Files

- `main_old_2026-08-11.pdf`, the paper as first published, with its OpenTimestamps proof `main_old_2026-08-11.pdf.ots`.
- `main.pdf`, the current version.
- source: `aistats2027.sty`, `main.tex`, `references.bib`.
- also: `main.aux`, `main.bbl`.
