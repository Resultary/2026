# Review

Independent mathematical audit completed on 2026-10-01 UTC.

- Correctness: **PASS**
- Originality: **PASS**
- Scientific value: **PASS**
- Disposition: **PASSED**

## Correctness

A fresh graph reconstruction gives 20 edges and exactly 16 minimal vertex covers with orbit types \((3,3,1)^5\), \((3,5,0)^5\), \((4,2,1)^5\), and \((5,0,1)\). Exact rational vertex enumeration gives the symmetry-reduced optimum \((p,q,s)=(3,2,4)/19\) with value \(29/19\). Independently checking all 3,656 half-integral fractional vertex covers gives the sharp certificate value \(29/38\), and enumerating all induced subsets gives 594 nonbipartite subsets with no disjoint pair. These facts reproduce \(\widehat\alpha(I)=29/19\) and \(\rho(I)=38/29\).

## Originality

The literature provides the general squarefree-monomial linear-programming framework and exact results for unicyclic edge ideals, but the Grötzsch graph is not unicyclic. No inspected source or independent record gives the two exact M4 values, and the resurgence upper bound uses a graph-specific domination certificate and odd-cycle-packing property.

## Scientific value

The Grötzsch graph is a canonical small triangle-free 4-chromatic graph. Pinning both the Waldschmidt constant and resurgence with a sharp graph-specific fractional/integral packing argument is a natural exact invariant computation and a useful benchmark beyond the previously covered unicyclic families.

## Limitations

- The finite half-integral certificate check was independently recomputed numerically with linear programming; the exact archived rational certificates remain the publication-grade proof objects.
- The stable Harbourne containment is not counted as the original contribution.
