# Q14 — Toward Fermionic Matter from Projective Dirac Admissibility: Chirality and Electroweak Structure Require a Lorentzian Spin Solder and a Distinct Weak Factor

J. Beau, Independent Researcher, France

## Status

Preprint. DOI: [10.5281/zenodo.20218409](https://doi.org/10.5281/zenodo.20218409)

## Abstract

The gauge–gravity synthesis of the Cosmochrony programme reads gravity and Yang–Mills dynamics,
conditionally, as the $a_2$ and $a_4$ Seeley–DeWitt responses of one admissible spectral functional.
This paper asks what the fermionic sector requires when fermions are sought in the Weil module of the
admissible fibre on a supplied Heisenberg carrier, which every result inherits.

1. **Algebra (proved on supplied model data)**: the finite carrier acts through
   $\operatorname{SL}(2,\mathbb{Z}/q\mathbb{Z})$, so a real metaplectic model and a doublet carrying its Lie
   algebra are supplied. Given them, $\mathfrak{mp}(2,\mathbb{R})_\mathbb{C} \simeq \mathfrak{sl}_2(\mathbb{C})$;
   the symmetric square of the doublet is the adjoint and its exterior square the trivial line, and a
   Hermitian form selects the compact real form $\mathfrak{su}(2)$. Given the supplied Born–Infeld datum (hypotheses (H1)–(H2) of
   O30), the internal parity $HK$ satisfies $(HK)^2 = -1$ without any metric.

2. **Two hypotheses, supplied by no source**: [H-Spin] identifies the $\operatorname{SL}(2,\mathbb{C})$
   acting on the doublet with the spin group of a four-dimensional Lorentzian co-metric; the geometric
   branch supplies such a co-metric only conditionally (Q5b, Q8, Q11). [H-Weak] supplies a distinct
   rank-two weak factor $E_{\mathrm{weak}}$: by Schur's lemma a weak action commuting with Lorentz
   transformations cannot act on the same copy of the doublet. Under [H-Spin],
   $\operatorname{Sym}^2(S_L)$ is a Lorentz sector and $\wedge^2(S_L)$ carries no hypercharge. Both are missing identifications, not refutations.

3. **Chirality and hypercharge (conditional)**: under [H-Spin], the projected Dirac operator
   $\mathcal{D}_{\Pi,g,A}$ contains a canonical zero-order endomorphism $E_\Pi$, the spinorial lift of the
   parity is unique up to a phase and reverses chirality, and, given the Born–Infeld datum and the
   orientation-compatible branch (an input), $E_\Pi$ is left-admissible, $P_R E_\Pi P_R = 0$; a non-zero
   left-admissible $E_\Pi \preceq 0$ must break that parity. The
   chiral selection of the weak interaction ($V-A$) and the anomaly constraints on the hypercharge
   weights require [H-Weak] as well; left-admissibility does not select the chiral assignment. The
   hypercharge selection needs in addition $Y_e \neq 0$, which excludes the known degenerate solution
   (the $U(2)$ structure of [H-Weak] already excludes it), and holds up to sign, rescaling and the
   exchange of $u_R$ and $d_R$.

4. **Generation multiplicity (conditional)**: the supplied rank-three selection rule
   $\sigma_c(n_3) = 3$ (O23) admits a spinorial multiplicity reading, giving a gauge-singlet
   three-generation factor $\mathbb{C}^3_{\mathrm{gen}} \subset \ker(\operatorname{ad}_{\operatorname{SU}(2)} \oplus Y)$,
   conditional also on [H-Spin] and [H-Weak] through the bundle it multiplies.
   The quark sector uses a supplied colour module; O31 is a withdrawal notice and no
   $\operatorname{SU}(3)$ is derived.

5. **Generation splitting (qualitative)**: a static $J_\Pi$-real, weight-preserving restriction cannot
   split the outer pair; in a metaplectic step model on a distinct generation doublet, the ordered step
   generator $\mathcal{G}_g = \log g$ carries the exact $J_3$ component $\alpha = ts\,\theta/\sinh\theta$
   ($\cosh\theta = 1 + ts/2$) and no mixing component, for any $\mathfrak{sl}_2(\mathbb{C})$ generator. Its
   identification with an emergent ordering derivative is not supplied, and the amplitude is open.

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
