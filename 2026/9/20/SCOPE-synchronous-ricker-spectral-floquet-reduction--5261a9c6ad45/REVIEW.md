# Review status

Fresh independent mathematical audit: **passed** on 2026-10-01 UTC.

## Final claim

For a row-regular Ricker competition matrix \(A\mathbf1=c\mathbf1\), the monodromy of any positive synchronous scalar \(p\)-cycle is exactly \(P_p(A)\) with \(P_p(\lambda)=\prod_{k=0}^{p-1}(1-(w_k/c)\lambda)\). Hence its Floquet multipliers are \(P_p(\sigma(A))\), and any nonzero interaction eigenvalue with \(\operatorname{Re}\lambda\le0\) forces linear instability for every positive synchronous period.

## Correctness

At a synchronized point \(z_k\mathbf1\), direct differentiation gives \(J_k=e^{r-w_k}(I-z_kA)=(z_{k+1}/z_k)(I-(w_k/c)A)\). All factors commute because they are polynomials in one matrix, and the scalar multipliers telescope around the cycle, proving the exact monodromy polynomial. Polynomial spectral mapping gives every Floquet multiplier, including the scalar Ricker multiplier at \(\lambda=c\). For \(t>0\), \(|1-t\lambda|^2=1-2t\operatorname{Re}\lambda+t^2|\lambda|^2>1\) whenever \(\lambda
e0\) and \(\operatorname{Re}\lambda\le0\), proving the period-independent obstruction. Independent checks of the cyclic-spectrum geometry reproduce the stated even/odd thresholds.

## Originality

Generic master-stability theory decomposes synchronized dynamics by coupling/network modes, and Ricker literature studies planar symmetric cycles and coupled almost-periodic maps. The inspected Ricker sources do not state that, for an autonomous row-regular competition matrix, every Jacobian along a synchronous cycle is an affine polynomial in the same competition matrix and hence the whole monodromy is exactly \(P_p(A)\). Resultary likewise found no earlier record with the exact formula or the resulting all-period left-half-plane obstruction.

## Value

The formula collapses an arbitrary-dimensional period-\(p\) Floquet product to evaluation of one explicit polynomial on the interaction spectrum. That provides reusable stability tests and a topology/spectrum obstruction uniform over every positive period, a meaningful structural simplification in multispecies discrete competition.

## Residual risks and limits

- The full theorem text of Ryals–Sacker (2022) was access-restricted on the inspected publisher route; its abstract states an \(N\)-dimensional identical-coefficient result under modest coupling constraints, so hidden overlap beyond the abstract remains a residual originality risk.
- Older planar symmetric-cycle literature may contain special low-period instances of the polynomial reduction; no arbitrary-dimension row-regular formula or period-independent left-half-plane obstruction was located.

This audit is a mathematical review, not external peer review, formal verification, or a guarantee of priority.
