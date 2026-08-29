# Q14 — Fermionic Matter and Chirality from Projective Dirac Admissibility

J. Beau, Independent Researcher, France

## Status

Preprint. DOI: [10.5281/zenodo.20218409](https://doi.org/10.5281/zenodo.20218409)

## Abstract

The preceding gauge–gravity synthesis of the Cosmochrony programme showed that gravity and Yang–Mills
dynamics arise from the $a_2$ and $a_4$ Seeley–DeWitt responses of the same admissible spectral
functional. The present paper extends this principle to the fermionic sector. Fermions are not
introduced as external matter fields. They arise as the spinorial face of the Weil module carried by
the admissible fibre on a supplied Heisenberg carrier, once its metaplectic Lie-algebraic structure
is complexified by the Lorentzian metric established in the geometric branch of the programme. That
carrier is supplied rather than selected by the axioms, so every result below inherits it.

Three structural results are proved:

1. **Electroweak spinor bundle**: The admissible Weil module $V_\rho$ induces, through its metaplectic
   lift and the Lorentzian complexification
   $\mathfrak{mp}(2,\mathbb{R})_\mathbb{C} \simeq \mathfrak{sl}_2(\mathbb{C})$, an admissible spinor
   bundle $S_\Pi$ whose symmetric and determinant tensor sectors reproduce the
   $\operatorname{SU}(2)_L \times U(1)_Y$ electroweak bundle structure. This result is conditional on
   the supplied Heisenberg carrier that fixes $F_n \simeq V_\rho$: Foundation and
   HeisenbergStructure establish that the axioms force irreducibility and non-commutation but select
   no finite Heisenberg group, an explicit $\mathfrak{S}_3$ countermodel satisfying the extracted
   carrier contract.

2. **Chiral structure and hypercharge rigidity**: The projected Dirac operator
   $\mathcal{D}_{\Pi,g,A}$ contains a canonical zero-order endomorphism $E_\Pi$, the internal
   spectral residue of non-injective projection. Under the spinorial lift of BI parity, $E_\Pi$ is
   left-admissible and produces the $V-A$ chiral structure. The $\gamma_5$-weighted $a_4$ coefficient
   then imposes anomaly-cancellation trace constraints on the hypercharge weights, which are thereby
   not free parameters but spectral coherence data.

3. **Three-generation multiplicity**: The admissible saturation invariant $\sigma_c(n_3) = 3$, a
   supplied selection rule (O23 Theorem 3.1 proves the three-dimensionality of the neutral sector
   of a supplied spinor carrier; carrier selection and observable identification are open), admits
   a spinorial multiplicity reading, yielding conditionally a gauge-singlet three-generation factor
   $\mathbb{C}^3_{\mathrm{gen}} \subset \ker(\operatorname{ad}_{\operatorname{SU}(2)} \oplus Y)$.
   The colour-coupled quark sector is obtained by tensoring with a colour module $V_{\mathrm{color}}$
   that is a supplied input rather than a derived one: O31 is a withdrawal notice, and
   $[H\text{-color}]_{\mathrm{pointwise}}$ is among the results it withdraws. Both the quark sector
   and the hypercharge selection of Theorem B are conditional on that supplied module; the $V-A$
   structure, the spinorial lift of BI parity, the leptonic carrier and the generation factor carry
   no colour condition. All of them, colour-conditional or not, are stated relative to the supplied
   Heisenberg carrier above, which is upstream of and independent of the colour module.

4. **Dynamic lifting of the generation degeneracy**: A qualitative mechanism is identified by which
   the oriented spectral cascade lifts the static $J_\Pi$-protected degeneracy of the generation
   factor $\mathbb{C}^3_{\mathrm{gen}}$. The static obstruction is established explicitly; the
   oriented odd sector and the cascade bridge provide the lifting channel. The amplitude of the
   generational splitting remains deferred to the cascade normalisation.

## Position in the programme

Q14 is the fermionic extension of the gauge–gravity synthesis established in Q12–Q13. Together,
Q12–Q14 constitute the matter–geometry unification arc of the Q-series: Yang–Mills dynamics (Q12),
joint Einstein–Yang–Mills equations (Q13), and fermionic matter with chirality and generation
structure (Q14).

## Compilation

```bash
cd q14
bash compile.sh
# or manually:
pdflatex -output-directory=out tex/q14.tex
```
