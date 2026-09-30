# Q14 — Toward Fermionic Matter from Projective Dirac Admissibility: The Electroweak Spinor Algebra, and Chirality Conditional on a Lorentzian Spin Structure

J. Beau, Independent Researcher, France

## Status

Preprint. DOI: [10.5281/zenodo.20218409](https://doi.org/10.5281/zenodo.20218409)

## Abstract

The gauge–gravity synthesis of the Cosmochrony programme reads gravity and Yang–Mills dynamics,
conditionally, as the $a_2$ and $a_4$ Seeley–DeWitt responses of one admissible spectral functional.
This paper asks what the fermionic sector requires when fermions are read from the Weil module of the
admissible fibre on a supplied Heisenberg carrier, which every result inherits.

1. **Algebra (proved)**: the complexified metaplectic algebra is
   $\mathfrak{mp}(2,\mathbb{R})_\mathbb{C} \simeq \mathfrak{sl}_2(\mathbb{C})$; on the abstract doublet its
   symmetric square is the adjoint and its exterior square the trivial line, and a Hermitian form selects
   the compact real form $\mathfrak{su}(2)$. Given the supplied Born–Infeld datum (hypotheses (H1)–(H2) of
   O30), the internal parity $HK$ satisfies $(HK)^2 = -1$ without any metric.

2. **Two hypotheses, supplied by no source**: [H-Spin] identifies the $\operatorname{SL}(2,\mathbb{C})$
   acting on the doublet with the spin group of a four-dimensional Lorentzian co-metric; the geometric
   branch supplies such a co-metric only conditionally (Q5b, Q8, Q11). [H-Weak] supplies a distinct
   rank-two weak factor $E_{\mathrm{weak}}$: by Schur's lemma a weak action commuting with Lorentz
   transformations cannot act on the same copy of the doublet, so $\operatorname{Sym}^2(S_L)$ is a Lorentz
   sector and $\wedge^2(S_L)$ carries no hypercharge. Both are missing identifications, not refutations.

3. **Chirality and hypercharge (conditional)**: under [H-Spin], the projected Dirac operator
   $\mathcal{D}_{\Pi,g,A}$ contains a canonical zero-order endomorphism $E_\Pi$, the spinorial lift of the
   parity is unique and reverses chirality, and $E_\Pi$ is left-admissible, $P_R E_\Pi P_R = 0$. The
   chiral selection of the weak interaction ($V-A$) and the anomaly constraints on the hypercharge
   weights require [H-Weak] as well; left-admissibility does not select the chiral assignment.

4. **Generation multiplicity (conditional)**: the supplied rank-three selection rule
   $\sigma_c(n_3) = 3$ (O23) admits a spinorial multiplicity reading, giving a gauge-singlet
   three-generation factor $\mathbb{C}^3_{\mathrm{gen}} \subset \ker(\operatorname{ad}_{\operatorname{SU}(2)} \oplus Y)$.
   The quark sector uses a supplied colour module; O31 is a withdrawal notice and no
   $\operatorname{SU}(3)$ is derived.

5. **Generation splitting (qualitative)**: a static $J_\Pi$-real, weight-preserving restriction cannot
   split the outer pair; in a metaplectic step model the ordered step generator $\mathcal{G}_g = \log g$
   carries a non-zero $J_3$ component. Its identification with an emergent ordering derivative is not
   supplied, and the amplitude is open.

## Position in the programme

Q14 is the fermionic step after the gauge–gravity synthesis of Q12–Q13. It isolates what the fermionic
sector needs beyond the admissible Weil fibre: a Lorentzian spin solder ([H-Spin]) and a distinct weak
factor ([H-Weak]).

## Compilation

```bash
cd q14
bash compile.sh
# or manually:
pdflatex -output-directory=out tex/q14.tex
```
