# Schur-Positivity of Complete Multipartite Graphs

This repository accompanies the paper:

**“A Schur-Positivity Classification for Complete Multipartite Graphs”**  
Ethan Shelburne and Steph van Willigenburg

## Overview

We classify complete multipartite graphs according to whether their chromatic symmetric functions are Schur-positive. Using special rim hook $G$-tabloids and combinatorial arguments, we extend known classifications for bipartite and tripartite graphs to all complete multipartite graphs.

The main result shows that a complete multipartite graph $K_\lambda$ (with at least two parts) is Schur-positive if and only if:

- All parts have size $1$ or $2$, or  
- $\lambda = (3,2^\beta)$ for $\beta \ge 1$.

## Contents

- `main.tex` – LaTeX source of the paper  
- `sections/` – Structured sections of the manuscript  
- `code/` – Computational verification of formulas and Schur coefficients  
- `figures/` – TikZ and diagram assets  

## Computational Notes

This repository includes code used to verify formulas for Schur coefficients and to compute quantities such as the number of spanning non-increasing sequences in incomparability graphs.
