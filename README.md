# Q12 — Yang–Mills Dynamics from Projective Spectral Entropy

**Yang–Mills Dynamics from Projective Spectral Entropy:
Vertical Heat-Kernel Variation on the Admissible Fibre**

J. Beau, Independent Researcher, France

## Abstract

The companion paper (Gravity) showed that the horizontal variation of the projective
spectral entropy functional $S_\Pi[g] = \tfrac{1}{2}\log\det' A_g$ with respect to the
base metric produces the Einstein tensor as the infrared-dominant response, via the
Seeley–DeWitt coefficient $a_2$.

The present paper carries out the complementary vertical variation: extending $A_g$ to a
Laplace-type operator $A_{g,\mathcal{A}} = -(\nabla^{\mathcal{A}})^2 + E$ on the associated
vector bundle of the admissible principal fibre, we compute the Seeley–DeWitt coefficient
$a_4$ for the total operator and extract the Yang–Mills term
\[
  c_{\mathrm{YM}} \int \mathrm{Tr}(F_{\mu\nu} F^{\mu\nu})\,\sqrt{g}\,\mathrm{d}^4 x.
\]

Variation of $S_\Pi[g, \mathcal{A}]$ with respect to the admissible connection $\mathcal{A}$
then yields the Yang–Mills equations $D_\mu F^{a\mu\nu} = 0$ in the current-free sector.

The induced gauge coupling $g_{\mathrm{YM}}^{-2} \sim (12 \cdot 16\pi^2)^{-1}\log(\Lambda/\mu)$
is logarithmic in the UV cutoff, while Newton's constant $G_N^{-1} \sim \ell_{\mathrm{sp}}^{-2}$
is quadratic. This spectral hierarchy is a structural consequence of the Seeley–DeWitt
expansion and does not require a separate input.

The gauge group $G_\Pi$ is taken as input from the spectral admissibility programme (Q6a,
O31); the SU(3) sector inherits the conditional status [H-color] of O31/O32.

**Central message**: $a_2 \to \text{Einstein}$, $a_4 \to \text{Yang–Mills}$, from the
single functional $S_\Pi[g, \mathcal{A}]$.

Beyond deriving both interactions, the paper identifies a conceptual principle: gravity and
gauge dynamics are separated by geometric direction (horizontal vs. vertical variation on
the admissible bundle) and by spectral order ($a_2$ vs. $a_4$ in the Seeley–DeWitt
hierarchy), not by a missing symmetry group. The difficulty of incorporating gravity into
the Standard Model framework may reflect a difference of spectral order rather than an
absent symmetry. The natural organisational space for unification in this framework is
therefore spectral and variational, not primarily group-theoretic.

## Key Result

**Theorem (Yang–Mills from $a_4$)**: Let $G_\Pi$ be the admissible gauge group derived in
Q6a/O31, and let $A_{g,\mathcal{A}}$ be the Laplace-type operator on the associated vector
bundle. Then:

1. $a_4(A_{g,\mathcal{A}}) \supset \dfrac{1}{16\pi^2} \int \dfrac{1}{12}\,\mathrm{Tr}(\Omega_{\mu\nu}\Omega^{\mu\nu})\,\sqrt{g}\,\mathrm{d}^4 x$

2. $S_\Pi[g, \mathcal{A}] \supset \dfrac{1}{12 \cdot 16\pi^2}\,\log\!\left(\dfrac{\Lambda}{\mu}\right) \int \mathrm{Tr}(F_{\mu\nu}F^{\mu\nu})\,\sqrt{g}\,\mathrm{d}^4 x$

3. $\dfrac{\delta S_\Pi}{\delta \mathcal{A}^a_\nu} = 0 \implies D_\mu F^{a\mu\nu} = 0$

## Status

Draft preprint. Zenodo: https://doi.org/10.5281/zenodo.20189137

## Position in the Programme

- **Depends on**: Gravity paper ($S_\Pi[g]$ functional, $a_2$ Einstein result), Q6a (gauge
  group $G_\Pi = \mathrm{SU}(3)\times\mathrm{SU}(2)\times\mathrm{U}(1)$), Q11 (effective
  Lorentzian metric)
- **Feeds into**: Q13 (Gauge–Gravity Spectral Synthesis: joint equations, hierarchy ratio,
  Born–Infeld completion)
- **Inherited conditionality**: SU(3) sector conditional on [H-color] (confirmed numerically
  in O32 for $q \in \{61, 151, 211\}$; analytical proof open)

## Compilation

```bash
cd q12
bash compile.sh
# or manually:
pdflatex -output-directory=out tex/q12.tex
```
