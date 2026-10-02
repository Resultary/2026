# Review status

Fresh independent mathematical audit: **passed** on 2026-10-01 UTC.

## Final claim

For exact unpreconditioned GMRES(1)/minimal residual iteration on every real symmetric nonsingular system, one cycle satisfies \(\|e_{k+1}\|_2/\|e_k\|_2\le2/\sqrt3\), and the constant is sharp. A two-eigenvalue indefinite equality case returns to the same error direction after two steps with factor \(2/3\), while its residual decreases on each step.

## Correctness

Diagonalizing the symmetric matrix and writing squared error coordinates as weights gives \(\alpha=m_3/m_4\) and the constraint \(\sum_iw_i z_i^3(1-z_i)=0\) for \(z_i=\alpha\lambda_i\). The exact identity \(4/3-(1-z)^2-12z^3(1-z)=(6z^2-3z-1)^2/3\) then averages to the squared-error bound \(4/3\). Independent symbolic recomputation gave zero residual in this identity, reproduced \(\alpha_0=1\), squared ratio \(4/3\), \(\alpha_1=-2\), and the two-step factor \(2/3\) for the stated \(\sqrt{33}\) witness. The definite and nonsymmetric boundary statements also follow from the displayed moment and triangular examples.

## Originality

He’s full arXiv text analyzes GMRES(1) residual root/q-linear convergence and states worst-case factor one for symmetric indefinite systems; it does not give the Euclidean solution-error one-step bound. Meurant gives formulas and estimators for solution-error norms in full FOM/GMRES, and Weiss emphasizes that residuals may decrease while errors increase, but neither inspected source states the sharp \(2/\sqrt3\) GMRES(1) transient bound or equality cycle. Resultary searches likewise found no covering record.

## Value

The theorem gives a sharp dimension-free cap on a practically important failure mode of residual minimization, with exact equality geometry and a recurring spike example. It cleanly separates residual contraction from solution-error transients and contrasts symmetric with nonsymmetric behavior, making it a motivated numerical-linear-algebra boundary theorem rather than a routine estimate.

## Residual risks and limits

- Fridman’s 1963 paper is historically plausible but its full text could not be inspected: open routes yielded metadata only and the authorized institutional retrieval reached human verification. That verification block was not retried or bypassed.
- Older minimum-error/minimum-residual literature could contain an equivalent one-step inequality under different terminology; no decisive implication was found in the material read.

This audit is a mathematical review, not external peer review, formal verification, or a guarantee of priority.
