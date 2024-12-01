# nonstandard

Generic implementation of nonstandard analysis in Lean 4; in particular, with a polymorphic `🞵(...)` operator and a `transfer_principle` tactic to use theorems proved in the nonstandard universe in the standard universe, and vice versa. In contrast, mathlib4 only includes definitions specific to the hyperreals $\ast\mathbb R$ (nonstandard-ly written as `ℝ*` in mathlib4).

The construction and transfer principle is by the usual mathlib4 ultrafilter. Importantly, no new axioms are assumed.

Significant inspiration is taken from Jacques D. Fleuriot and Brian Huffman’s Isabelle/HOL implementation [1–3], and of course Abhimanyu Pallavi Sudhir’s existing implementation for `ℝ*` included in mathlib4.

## References
1. Fleuriot, J. D. (2000, September). Nonstandard geometric proofs. In International Workshop on Automated Deduction in Geometry (pp. 246-267). Berlin, Heidelberg: Springer Berlin Heidelberg.
2. Fleuriot, J. D., & Paulson, L. C. (2000). Mechanizing nonstandard real analysis. LMS Journal of Computation and Mathematics, 3, 140-190.
3. Fleuriot, J. (2001). A combination of geometry theorem proving and nonstandard analysis with application to Newton’s Principia. Springer Science & Business Media.
4. Fleuriot, J., & Fleuriot, J. (2001). Nonstandard Real Analysis. A Combination of Geometry Theorem Proving and Nonstandard Analysis with Application to Newton’s Principia, 99-126.
5. Huffman, B. (2005). Transfer principle proof tactic for nonstandard analysis. NetCA, 18-26.
6. Abhimanyu Pallavi Sudhir. Ultraproducts and hyperreal analysis.
