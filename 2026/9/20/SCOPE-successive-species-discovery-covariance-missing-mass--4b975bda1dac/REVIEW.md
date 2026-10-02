# Review status

Fresh independent mathematical audit: **passed** on 2026-10-01 UTC.

## Final claim

For iid sampling from any countable species law, \(\operatorname{Cov}(D_{n+1},D_{n+2})=\operatorname{Var}(M_n)-(m_n-m_{n+1})(1-m_n)\). For every fixed \(n\ge1\), finite species laws realize both covariance signs; a one-common-species plus many-equal-rare-species family has a positive diffuse-tail limit.

## Correctness

Conditioning on the first \(n\) draws gives the exact ordered-distinct-unseen probability \(M_n^2-Q_n\). Since \(\mathbb E Q_n=m_n-m_{n+1}\), subtracting \(m_nm_{n+1}\) yields the stated covariance decomposition. The uniform law gives a strictly negative closed form. For one atom of mass \(1-a\) plus \(K\) atoms of mass \(a/K\), direct expansion gives a covariance tending to \(a^{n+1}(1-a)^2(1-a^n)>0\), so sufficiently large finite \(K\) gives positive covariance for every fixed \(n\). The package’s rational-arithmetic artifact was inspected as reproducibility evidence, but the proof rests on these analytic identities.

## Originality

The closest modern full-text source, Chebunin–Zuyev, develops process-level covariance formulas for occupancies and missing mass under regular variation but does not state the finite-sample covariance of two adjacent discovery indicators or the heterogeneity-minus-depletion decomposition. Classical discovery-probability papers estimate the one-step new-species probability rather than this dependence law. Resultary returned no stronger published SCOPE claim covering the identity and both-sign theorem.

## Value

The identity separates two competing mechanisms—random missing-mass heterogeneity and deterministic depletion—and answers a natural dependence-sign question with explicit finite examples of both signs at every burn-in. It is a reusable structural relation in species sampling rather than a routine recomputation of a known table.

## Residual risks and limits

- The adjacent-discovery identity is elementary enough that an equivalent formula may exist in older urn, occupancy, or species-sampling literature under different terminology; no such implication was located in the inspected sources.

This audit is a mathematical review, not external peer review, formal verification, or a guarantee of priority.
