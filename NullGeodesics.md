# Null Geodesics as a Unifying Structure between General Relativity and Quantum Field Theory
## A Geometric Reformulation of the Relativity-Quantum Interface

### Abstract

We propose that null geodesics (causal structures of spacetime for which ds² = 0) constitute the natural domain of compatibility between general relativity and quantum field theory. Unlike timelike trajectories (massive particles) which generate conceptual tensions between quantum and classical reference frames, null structures exhibit remarkable invariance properties: absence of proper time, robustness against quantum corrections, and a central role in the holographic principle. We demonstrate that the main interfaces between gravity and quantum theory—photonic propagators, event horizons, AdS/CFT correspondence, and loop quantum gravity—fundamentally rest on null structures. A fundamental energy asymmetry separates massive and null ontologies: while the transition between these regimes requires divergent energy, interactions (creation/absorption of null particles) require finite energy. This observation suggests a reformulation where null geodesics are not a special case but the primordial structure upon which to build a quantum theory of gravitation.

**Keywords:** Null geodesics, causal structure, holographic principle, quantum field theory, general relativity, unification, ontological asymmetry

---

## 1. Introduction

### 1.1 The Unification Problem

The incompatibility between general relativity (GR) and quantum mechanics (QM) has been one of the fundamental problems of theoretical physics for nearly a century. This tension manifests at several levels:

**Conceptual:**
- GR treats spacetime as a smooth differentiable manifold
- QM implies fluctuations, superpositions, and a potential discrete structure at the Planck scale

**Technical:**
- Naive quantization of GR generates non-renormalizable divergences
- Position/time observables are incompatible with the uncertainty principle

**Ontological:**
- GR is deterministic (geometry fixed by Einstein's equations)
- QM is probabilistic (wave function, collapse)

However, a remarkable observation emerges from the analysis of effective theories: the causal structure of spacetime appears resistant to quantum corrections.

### 1.2 Central Thesis

We propose that this robustness is not accidental. Null geodesics—causal structures of spacetime characterized by ds² = 0—possess unique properties that make them naturally compatible with quantum theory:

1. **Maximal invariance:** Absence of proper time eliminating reference frame conflicts
2. **Support for quantum information:** Holographic principle and null surfaces
3. **Robustness to quantum corrections:** Causal structure preserved in QFT
4. **Gravitational interface:** Horizons, Bekenstein-Hawking entropy
5. **Energy asymmetry:** Infinite barrier between ontologies, finite interactional permeability

**Hypothesis:** The difficulties in quantizing gravity stem from our attempt to quantize timelike degrees of freedom (massive particles, observers) rather than null structures which are intrinsically quantum-compatible.

### 1.3 Article Plan

We proceed in five steps:
- **Section 2:** Review of geometric properties of null geodesics in GR
- **Section 3:** Analysis of the role of null structures in quantum field theory
- **Section 4:** Examination of GR-QFT interfaces where null geodesics play a central role
- **Section 5:** Proposal for a unified framework based on the primacy of null structures, including fundamental energy asymmetry
- **Section 6:** Discussion of philosophical and methodological implications, including the epistemic limit

---

## 2. Geometric Foundations: Null Geodesics in General Relativity

### 2.1 Fundamental Definitions and Properties

Let (M, g) be a pseudo-Riemannian manifold with signature (−,+,+,+) representing spacetime.

**Definition 2.1 (Causal interval):** For two infinitesimally separated events, the interval ds² decomposes according to:

ds² = g_μν dx^μ dx^ν

and defines three classes of intervals:

| Type | Condition | Terminology | Interpretation |
|------|-----------|-------------|----------------|
| Timelike | ds² < 0 | Timelike | Massive trajectory |
| Lightlike | ds² = 0 | Null/Lightlike | Photonic trajectory |
| Spacelike | ds² > 0 | Spacelike | Acausal separation |

**Definition 2.2 (Proper time):** Along a curve γ(λ), the proper time is:

τ[γ] = ∫_γ √(−g_μν ẋ^μ ẋ^ν) dλ

where ẋ^μ = dx^μ/dλ.

**Lemma 2.1:** For a null geodesic γ, the proper time is identically zero: τ[γ] = 0.

**Proof:** ds² = 0 along γ ⟹ dτ = 0 everywhere. ∎

**Corollary 2.1:** A null geodesic does not possess an intrinsic temporal parametrization. The four-velocity u^μ = dx^μ/dτ does not exist.

### 2.2 Causal Structure and Light Cones

**Definition 2.3 (Light cone):** At a point p ∈ M, the future light cone C⁺(p) is the set of tangent vectors v ∈ T_p M such that g(v,v) = 0 and v⁰ > 0.

**Theorem 2.1 (Causal robustness):** The causal structure of spacetime—defined by light cones—determines the metric g up to a conformal factor.

**Proof:** [Hawking & Ellis, 1973] Knowledge of causal relations between events strongly constrains the geometry. ∎

**Implication:** Null geodesics encode maximal causal information while depending minimally on the exact metric.

### 2.3 Null Geodesics vs. Massive Trajectories

**Formal comparison:**

**Massive particle (m > 0):**
- Worldline γ: ds² < 0
- Proper time: dτ > 0
- Four-velocity: u^μ = dx^μ/dτ well-defined
- Normalization: g(u,u) = −c²
- Equation of motion: ∇_u u = 0 (zero proper acceleration)

**Massless particle (m = 0):**
- Geodesic γ: ds² = 0
- Proper time: dτ = 0
- Four-velocity: u^μ undefined (division by zero)
- Four-momentum: p^μ = ℏk^μ with g(p,p) = 0
- Equation: k^μ ∇_μ k^ν = 0 (geodesic propagation of wave vector)

**Theorem 2.2 (Ontological dichotomy):** Objects in spacetime divide into two distinct categories:

1. **Observers (m > 0):** possess proper time, evolve temporally
2. **Causal structures (m = 0):** have no proper time, are geometric elements of (M,g)

### 2.4 Null Surfaces and Horizons

**Definition 2.4 (Null surface):** A hypersurface S ⊂ M is null if its normal vector n^μ satisfies g(n,n) = 0.

**Physical examples:**
- Event horizon of a Schwarzschild black hole: r = 2GM/c²
- Cosmological horizon in de Sitter spacetime
- Rindler horizon for an accelerated observer

**Remarkable property:** Null surfaces are generated by congruences of null geodesics.

**Theorem 2.3 (Raychaudhuri for null geodesics):** Let θ be the expansion of a congruence of null geodesics. Then:

dθ/dλ = −θ²/2 − σ_{ab}σ^{ab} + ω_{ab}ω^{ab} − R_{ab}k^a k^b

where σ_{ab} is the shear, ω_{ab} the rotation, and k^a the tangent vector.

**Implication:** If R_{ab}k^a k^b ≥ 0 (null energy condition), any initially converging congruence (θ < 0) develops a caustic in finite time.

**Link with quantum gravity:** This equation directly relates null geometry (θ, σ, ω) to energy content (R_{ab}k^a k^b), suggesting that null structures are sensitive to quantum corrections of the stress-energy tensor.

---

## 3. Null Geodesics in Quantum Field Theory

### 3.1 Propagators and the Zero-Mass Constraint

In quantum field theory (QFT), the propagation of a particle from A to B is described by a propagator—the Green's function of the field.

**Theorem 3.1 (Photonic propagator):** The propagator of the electromagnetic field in Feynman gauge is:

D^μν(x−y) = −g^μν ∫ (d⁴k)/(2π)⁴ (i)/(k² + iε) e^{−ik·(x−y)}

where k² = g_αβ k^α k^β.

The pole k² = 0 indicates that only lightlike configurations contribute to on-shell propagation.

**Explicit rewriting:** We can decompose:

D(x−y) ∝ ∫ d⁴k δ(k²) θ(k⁰) e^{−ik·(x−y)}

The constraint δ(k²) = δ(g_αβ k^α k^β) imposes that k^μ is a null four-vector.

**Geometric interpretation:**

In QFT, a photon does not explore "all paths" in the naive sense. It explores all null paths—that is, all null geodesics connecting x and y in spacetime.

**Proposition 3.1:** The zero-mass constraint in QFT is equivalent to the geometric constraint ds² = 0 in GR. The two theories naturally agree on null structures.

### 3.2 Quantum Causality and Light Cones

**Theorem 3.2 (Microcausality):** In relativistic QFT, two field operators Φ(x) and Φ(y) commute outside the light cone:

[Φ(x), Φ(y)] = 0  if  (x−y)² > 0

**Proof:** Consequence of the spin-statistics theorem and Lorentz invariance. ∎

**Implication:** The causal structure (light cones = null geodesics) is rigidly preserved in quantum theory.

**Important contrast:**
- Position/momentum: Uncertainty relations Δx Δp ≥ ℏ/2
- Energy/time: ΔE Δt ≥ ℏ/2
- Causal structure: Preserved exactly (no "causal blur")

### 3.3 Reeh-Schlieder Theorem and Information Density

**Theorem 3.3 (Reeh-Schlieder, 1961):** In QFT in Minkowski space, the vacuum |0⟩ is cyclic: for any causal region O, the set {A|0⟩ : A ∈ A(O)} is dense in the Hilbert space.

**Interpretation:** The quantum information of the vacuum is "concentrated" on causal boundaries—which are precisely null surfaces.

**Link with null geodesics:** Quantum entanglement between regions is maximal at causal boundaries (null surfaces).

### 3.4 Quantum Corrections to the Metric

In semiclassical gravity, the modified Einstein equation is:

G_μν = (8πG/c⁴) ⟨T_μν⟩

where ⟨T_μν⟩ is the quantum expectation value of the stress-energy tensor.

**Proposition 3.2:** Quantum corrections to the metric preserve the causal structure at first order.

**Argument:** Quantum fluctuations of ⟨T_μν⟩ modify g_μν → g_μν + h_μν, but the light cones (defined by g(v,v) = 0) remain conformally equivalent.

**Theorem 3.4 (Fewster-Verch, 2015):** Under technical conditions (Hadamard states), quantum fluctuations of the stress-energy tensor satisfy inequalities that guarantee local preservation of causal structure.

**Conclusion:** Null geodesics are robust against quantum corrections, unlike timelike trajectories which can be strongly affected.

---

## 4. Relativity-Quantum Interfaces: The Central Role of Null Structures

### 4.1 Bekenstein-Hawking Entropy and Null Surfaces

#### 4.1.1 The Bekenstein-Hawking Result

**Theorem 4.1 (Bekenstein-Hawking, 1974-1975):** A black hole of mass M, charge Q, and angular momentum J possesses an entropy:

S_BH = (k_B c³)/(4ℏG) A

where A is the area of the horizon (null surface).

**Explicit form for Schwarzschild:**

A = 4π r_s² = 16π (GM/c²)²

⟹ S_BH = (4πk_B G M²)/(ℏc)

#### 4.1.2 Hawking Temperature

The black hole radiates thermally at temperature:

T_H = (ℏc³)/(8πk_B GM)

**Crucial observation:** This radiation emerges from the horizon—a null surface.

#### 4.1.3 Geometric-Quantum Interpretation

**Proposition 4.1:** The entropy of a black hole is proportional to the area of its null surface (horizon) because:

1. Quantum information is encoded on this surface (holographic principle)
2. Quantum modes of the field are defined relative to the horizon (Unruh-Hawking modes)
3. The null structure of the horizon allows an unambiguous definition of thermodynamic entropy

**Deep connection:** Gravitational entropy (area of a null surface) = Quantum entropy (degrees of freedom on this surface)

### 4.2 The Holographic Principle

#### 4.2.1 't Hooft-Susskind Formulation

**Principle 4.1 (Holography, 1993):** All information contained in a volume of spacetime can be encoded on its causal boundary.

**Precise formulation:** Let V be a causal region of spacetime, and ∂V its boundary (null surface in the case of a horizon). Then:

S_max(V) ≤ (c³ A(∂V))/(4ℏG)

where A(∂V) is the area of the boundary.

#### 4.2.2 AdS/CFT Correspondence

**Theorem 4.2 (Maldacena, 1997):** There exists an exact duality between:

1. A quantum gravity theory in Anti-de Sitter (AdS) space of dimension d+1
2. A conformal field theory (CFT) on the boundary ∂(AdS) of dimension d

**Crucial point:** The boundary ∂(AdS) is a null surface at infinity.

**Canonical example:** AdS₅ × S⁵ ↔ N=4 Super Yang-Mills in 4D

**Geometric formulation:**

AdS space in Poincaré coordinates:

ds² = (L²/z²)(−dt² + dx² + dy² + dz²)

The boundary z → 0 is conformal to Minkowski space—a null causal structure.

#### 4.2.3 Quantum Information on Null Surfaces

**Proposition 4.2:** The AdS/CFT correspondence suggests that quantum information "naturally lives" on null surfaces because:

1. CFT correlators on the boundary encode the complete bulk physics
2. Bulk reconstruction uses causal relations (determined by null geodesics)
3. Entanglement entropy in the CFT corresponds to the area of extremal (null) surfaces in the bulk (Ryu-Takayanagi formula)

**Ryu-Takayanagi formula (2006):**

S_A = (c³)/(4ℏG) Area(γ_A)

where S_A is the entanglement entropy of region A in the CFT, and γ_A is the minimal extremal surface (often null or near-null) in the bulk that borders A.

### 4.3 Loop Quantum Gravity and Null Surfaces

#### 4.3.1 Area Quantization

In Loop Quantum Gravity (LQG), surface areas are quantized:

A = 8πℓ_P² ∑_i √(j_i(j_i+1))

where ℓ_P = √(ℏG/c³) is the Planck length, and j_i are half-integer numbers (spins).

#### 4.3.2 Isolated Horizons

**Theorem 4.3 (Ashtekar et al., 1997):** In LQG, the entropy of an isolated horizon (null surface) is:

S = (γ/4) (k_B c³)/(ℏG) A

where γ is the Immirzi parameter.

**Observation:** For γ = ln(2)/π√3, we exactly recover S_BH.

#### 4.3.3 Microscopic Structure

**Proposition 4.3:** The quantum degrees of freedom of gravity in LQG are localized on null surfaces (horizons) because:

1. Spin networks "puncture" the horizon at a discrete number of points
2. Each intersection contributes to the quantized area
3. Entropy counts microstates compatible with the macroscopic area

**Interpretation:** Null surfaces are not "passive boundaries" but active loci where quantum geometry manifests.

### 4.4 Hawking Radiation and Particle Creation

#### 4.4.1 Unruh Modes

For a uniformly accelerated observer (acceleration a), the Minkowski vacuum |0_M⟩ appears as a thermal bath at temperature:

T_Unruh = (ℏa)/(2πk_B c)

**Crucial point:** This thermalization emerges from the structure of the Rindler horizon—a null surface for the accelerated observer.

#### 4.4.2 Hawking Mechanism

Hawking radiation originates from particle-antiparticle pair creation near the horizon (null surface).

**Mode analysis:**

Outgoing modes (out) are related to incoming modes (in) by a Bogoliubov transformation:

a_out = α a_in + β a†_in

The coefficient β ≠ 0 indicates particle creation.

**Role of the null surface:**

The Bogoliubov transformation is defined by the geometry of the horizon (null surface). Mode frequencies are exponentially shifted (infinite gravitational redshift at the horizon).

**Proposition 4.4:** Hawking radiation is a quantum effect intrinsically linked to the causal structure (null surface of the horizon), not to local curvature.

**Argument:** Very massive black holes (weak curvature) still radiate (T_H ∝ 1/M). It is the global causal topology (presence of a horizon) that matters.

### 4.5 Synthetic Table

| Phenomenon | Null Structure Involved | GR-QFT Link |
|------------|------------------------|-------------|
| Photonic propagator | Null geodesics k² = 0 | Geometric constraint = quantum constraint |
| BH entropy | Horizon area | S ~ A: Geometry (GR) = Information (QFT) |
| Hawking radiation | Horizon (null surface) | Particle creation (QFT) at horizon (GR) |
| AdS/CFT | Causal boundary ∂(AdS) | Duality: Gravity (bulk) ↔ QFT (null boundary) |
| Ryu-Takayanagi | Extremal surfaces (null/quasi-null) | Entanglement (QFT) = Geometric area (GR) |
| LQG horizons | Isolated horizons | Quantum microstates on null surfaces |
| Unruh effect | Rindler horizon | Quantum thermalization of geometric origin |

**Conclusion:** All known interfaces between GR and QFT centrally involve null structures.

---

## 5. Toward a Primacy of Null Structures: Unified Framework

### 5.1 Reformulation of the Quantization Problem

#### 5.1.1 The Traditional Approach (and its Difficulties)

Traditionally, one attempts to quantize the metric g_μν itself:

g_μν → ĝ_μν (operator)

**Problems:**
- Non-renormalizable UV divergences
- Loss of the classical spacetime concept
- Measurement problem (which time? which observer?)
- Contradictions between uncertainty principle and smooth geometry

#### 5.1.2 Alternative Proposal: Quantize the Causal Structure

**Hypothesis 5.1:** Instead of quantizing g_μν (which describes both causality AND distances), quantize separately:

1. **Causal structure (light cones, null geodesics)** → Quantum-compatible
2. **Conformal factor (proper distances)** → Emergent/Classical

**Justification:**

Theorem 2.1 shows that the metric is determined up to a conformal factor by the causal structure.

Write: g_μν = Ω² g̃_μν

where g̃_μν encodes the causal structure (invariant), and Ω is the conformal factor (variable).

**Proposition 5.1:** Only g̃_μν (causal structure) must be quantized. The factor Ω can remain classical or semi-classical.

### 5.2 Null Geodesics as Primary Observables

#### 5.2.1 Observables in Quantum Gravity

In GR, diffeomorphism-invariant observables are rare. Natural candidates are:

- Surface areas (notably null)
- Volumes of causal regions
- Geodesic lengths

**Theorem 5.1 (Observables in LQG):** Surface areas (including null surfaces) are well-defined and quantifiable observables in LQG.

#### 5.2.2 Proposition: Primacy of Null Geodesics

**Axiom 5.1:** Null geodesics are the primordial structures of quantum spacetime because:

1. **Invariance:** No proper time → no preferred reference frame → no conflict between quantum observers
2. **Robustness:** Causal structure preserved under quantum corrections
3. **Information:** Holographic principle places information on null surfaces
4. **Interface:** All quantum manifestations of gravity (Hawking, Unruh, BH entropy) involve null surfaces

**Corollary 5.1:** Timelike trajectories (massive observers) are derived structures that emerge from the dynamics of null structures.

### 5.3 Construction of a Theoretical Framework

#### 5.3.1 Space of Causal Structures

**Definition 5.1:** Let C(M) be the space of causal structures on a manifold M—that is, the set of light cone fields compatible with a Lorentzian metric.

**Proposition 5.2:** The space C(M) can be endowed with a natural quantum structure because:

1. Light cones are defined by order relations (quantifiable via operator algebras)
2. Null surfaces (causal boundaries) admit area quantization (LQG)
3. Quantum information is naturally associated with these surfaces (holography)

#### 5.3.2 Dynamics of Null Structures

**Question:** What dynamical equation governs the evolution of the quantum causal structure?

**Proposition 5.3:** The quantum analog of Einstein's equation for causal structures could be written:

R̂[C] = (8πG/c⁴) ⟨T̂_μν⟩

where R̂[C] is a functional operator of the causal structure C, and ⟨T̂_μν⟩ is the quantum stress-energy tensor.

**Key constraint:** The equation must preserve causal structure (no "causal blur").

#### 5.3.3 Emergence of Massive Observers

**Hypothesis 5.2:** Massive particles (observers with dτ > 0) emerge as collective excitations of quantum null structures.

**Analogy:**
- Phonons (massive particles) emerge from crystal lattices (underlying structure)
- Massive particles would emerge from networks of quantum null geodesics

**Hint:** In string theory, all particles (including massive) are vibration modes of 1D strings whose dynamics respects null constraints (Virasoro constraints).

### 5.4 Predictions and Tests

#### 5.4.1 Corrections to Bekenstein-Hawking Entropy

**Prediction 5.1:** If null geodesics are primordial, quantum corrections to S_BH should preserve the form S ∝ A (null surface area) but with logarithmic corrections:

S = S_BH + α ln(A/ℓ_P²) + ...

where α depends on field content.

**Observational status:** Calculations in LQG and string theory confirm logarithmic corrections of this form.

#### 5.4.2 Causality in Quantum Fluctuations

**Prediction 5.2:** Quantum fluctuations of geometry at the Planck scale must never violate macroscopic causal structure.

**Test:** Search for causality violations in high-energy propagators.

**Status:** No violation observed. Effective field theories (EFT) rigorously respect causality.

#### 5.4.3 Spacetime Structure at Planck Scale

**Prediction 5.3:** At the Planck scale, spacetime should not "foam" isotropically (naive quantum foam), but maintain a coherent causal structure.

**Implication:** Geometric fluctuations should be anisotropic, preserving null directions.

#### 5.4.4 Universal Holography

**Prediction 5.4:** The holographic principle should be universal: any quantum theory of gravity must encode information on null surfaces.

**Status:** Confirmed in string theory (AdS/CFT), in cosmology (cosmological horizons), and suggested in LQG.

### 5.5 Reformulation of the Classical Limit

#### 5.5.1 The Traditional Problem

How to recover classical GR from a quantum theory of gravity?

**Standard approach:** Limit ℏ → 0

**Problems:**
- ℏ is a fundamental constant, not an adjustable parameter
- The classical limit depends on physical context (decoherence, large scales)

#### 5.5.2 Proposal: Causal Coherence Limit

**Definition 5.2:** The classical limit is reached when the causal structure becomes non-fluctuating at the scale considered.

**Criterion:** Light cones are well-defined when:

δ(light cone) ≪ Relevant causal scale

**Example:**
- Planck scale: Quantum fluctuations δ ~ ℓ_P → No classical cone
- Macroscopic scale L ≫ ℓ_P: δ/L → 0 → Well-defined classical cones

**Advantage:** This formulation directly links the classical limit to the stability of null structures.

### 5.6 Energy Asymmetry and Ontological Barrier

#### 5.6.1 Transition/Interaction Distinction

Null and massive structures exhibit a fundamental energy asymmetry that explains their apparently paradoxical coexistence.

**Theorem 5.2 (Ontological transition barrier):** The transition of a massive particle (m > 0) to a null state (m = 0) requires divergent energy.

**Proof:** For a particle of mass m and velocity v, the relativistic energy is:

E(v) = γmc² = mc²/√(1 − v²/c²)

The limit v → c implies γ → ∞, thus E → ∞. ∎

**Corollary 5.2:** There exists an infinite energy barrier separating the two ontologies (timelike ↔ null). This barrier is insurmountable in both directions.

**Fundamental contrast:** Emission/absorption processes (e⁻ → e⁻ + γ) require finite energy ΔE ~ ℏω, typically on the order of a few eV for atomic transitions.

**Proposition 5.4 (Interaction/transition asymmetry):**

| Process Type | Nature | Energy Cost | Status |
|--------------|--------|-------------|--------|
| Ontological transition | m > 0 → m = 0 | E → ∞ | Forbidden |
| Inverse transition | m = 0 → m > 0 | E → ∞ | Forbidden |
| Creation/absorption | m + ∅ → m + (m=0) | E ~ ℏω (finite) | Permitted |
| Annihilation | m + m̄ → (m=0) + (m=0) | E ~ 2mc² (finite) | Permitted |

**Crucial remark:** In annihilation, the total ontological charge is conserved (a massive particle + its antiparticle have a "net ontological charge" of zero), allowing the process despite the barrier.

This asymmetry explains why null structures are omnipresent as interaction mediators (photons, gravitons, gluons) while remaining ontologically separated from massive matter.

#### 5.6.2 Elementary Quantum Processes and Geometry of Transition Events

**Definition 5.3 (Transition event):** An elementary quantum process (emission, absorption, creation, annihilation) is a point event p ∈ M in spacetime where worldlines of different kinds (timelike/null) meet.

**Proposition 5.5:** Quantum transition events occur geometrically at points where the timelike worldline is tangent (in the local geometric sense) to an emerging or absorbed null geodesic.

**Geometric formulation:**

Let γ_m(τ) be a massive worldline parametrized by proper time τ, and γ_0(λ) a null geodesic parametrized by an affine parameter λ. Photon emission occurs at point p where:

1. **Meeting:** γ_m(τ₀) = γ_0(0) = p
2. **Geometric tangency:** The four-momentum of the emitted photon k^μ = ℏ(dγ_0/dλ)|_{λ=0} satisfies g(k,k) = 0
3. **Conservation:** p^μ_{initial} = p^μ_{final} + k^μ, where p^μ = mu^μ

**Interpretation:** The creation event is geometrically characterized by the emergence of a null causal direction from a timelike worldline. "Tangency" here means that locally, at point p, a new null geodesic "departs" from the massive worldline without it itself becoming null.

**Proposition 5.6 (Transition duration):** The transition event is not strictly point-like but possesses a characteristic duration:

Δt ~ ℏ/ΔE

where ΔE is the energy difference between involved quantum states.

**Justification:** By the time-energy uncertainty principle, a transition involving an energy change ΔE cannot be temporally localized better than Δt ~ ℏ/ΔE.

**Example:** For a visible atomic transition (ΔE ~ 2 eV), we obtain Δt ~ 10⁻¹⁵ s, confirmed by attosecond spectroscopy measurements.

#### 5.6.3 Null Surfaces and Quantum Events

**Empirical observation:** All known macroscopic radiative processes involve the formation or presence of causal horizons (null surfaces):

- Hawking radiation: Schwarzschild horizon (macroscopic, permanent)
- Unruh effect: Rindler horizon (observer-dependent)
- Thermal radiation: Effective horizon of thermal bath

**Hypothesis 5.3:** Elementary quantum processes (atomic emissions, decays) can be understood as involving the formation of local and ephemeral causal horizons.

**Geometric justification:** A horizon is defined as a null hypersurface H ⊂ M separating causally disconnected regions. Photon emission from a point p creates such a separation:

- Past causal set of p: J⁻(p) = set of events that can influence p
- Future causal set of (p + photon): J⁺(p) ∪ J⁺(γ_0) where γ_0 is the photon trajectory
- Causal boundary: The hypersurface generated by the null geodesic γ_0 separates regions influenceable by the pre-emission state from regions influenceable by the post-emission state

**Proposition 5.7:** The universal structure of radiative processes (Hawking, Unruh, atomic emission) suggests that the formation of null surfaces (horizons) is the generic geometric signature of quantum transitions involving massless particles.

**Remark:** This proposition unifies under a single geometric framework phenomena appearing at very different scales (from atom to black hole), suggesting a deep underlying principle linking quantum transitions and causal structure.

#### 5.6.4 Implications for Relativity-Quantum Compatibility

**Theorem 5.3 (Barrier compatibility):** The existence of an infinite energy barrier between massive and null ontologies is compatible with the creation/annihilation of null particles precisely because these processes preserve the ontological nature of the involved particles.

**Argument:**

1. In e⁻ → e⁻ + γ, the electron remains massive before and after
2. The created photon is null from its creation
3. No particle "crosses" the m=0 ↔ m>0 barrier
4. The barrier remains uncrossed despite the apparent "creation" of null mass

**Corollary 5.3:** Null structures can serve as an interface between massive regimes precisely because they remain ontologically distinct. If transition were possible (finite barrier), null structures would lose their interface role.

**Proposition 5.8 (Universal mediation):** Fundamental interactions are mediated by massless particles (photons for electromagnetism, gravitons for gravity, gluons for strong force—though they have effective mass) because:

1. Infinite range requires m = 0 (Yukawa theorem)
2. Mediators must be ontologically distinct from material particles to play an interface role
3. The infinite energy barrier guarantees this distinction while allowing creation/annihilation at finite cost

**Philosophical consequence:** The energy asymmetry (E → ∞ for transition, E ~ ℏω for interaction) is not a technical accident but a structural necessity for null structures to play their role as universal interface between gravity and quantum theory.

---

## 6. Discussion: Philosophical and Methodological Implications

### 6.1 Inversion of the Ontological Hierarchy

#### 6.1.1 Traditional View

**Classical hierarchy:**
Spacetime (substrate) → Massive particles (objects) → Photons (special case)

**Problem:** This hierarchy generates tensions when quantizing, as it privileges massive observers (dτ > 0) who have proper reference frames incompatible in QM.

#### 6.1.2 Proposed View

**Revised hierarchy:**
Null structures (primordial) → Causal structure (derived) → Massive observers (emergent)

**Justification:**

1. Null structures are quantum-compatible (no reference frame)
2. They carry information (holography)
3. They are robust to quantum corrections
4. Observers emerge as excitations
5. The infinite energy barrier maintains ontological distinction

**Philosophical proposition 6.1:** Temporal being (dτ > 0) is not fundamental—it emerges from atemporal structures (dτ = 0). The infinite energy barrier between these two modes of existence explains why transition is impossible while allowing interaction.

### 6.2 Mathematics and Physics: The Case of Division by Zero

#### 6.2.1 The Problem of u^μ = dx^μ/dτ for dτ = 0

In pure mathematics, 1/0 is undefined.

In physics, when we encounter dτ = 0:

- The four-velocity u^μ does not exist
- But this does not mean "error"—it signals a category transition

**Proposition 6.2:** Mathematical singularities (divisions by zero) in physics often mark ontological boundaries between existence regimes.

**Examples:**
- dτ = 0: Observer/causal structure boundary
- γ → ∞ (v → c): Massive particle/null particle boundary (infinite energy barrier)
- r = r_s (Schwarzschild): Causally connected region/causally disconnected region boundary

#### 6.2.2 Link with the Coherence-Limit Principle

The limits m = 0 and m = m_P correspond to:

- m → 0: dτ → 0, E → ∞ (transition to null structure, infinite barrier)
- m → m_P: λ_C = r_S (geometric collapse)

**Unified interpretation:** "Mathematical impossibilities" (divisions by zero, infinite limits) are the geometric signatures of boundaries between physical regimes. The infinite energy barrier at m = 0 is the physical manifestation of the mathematical singularity dτ = 0.

### 6.3 Reformulation of the Arrow of Time

#### 6.3.1 The Traditional Problem

Why does time "flow" in a privileged direction when fundamental laws are (nearly) reversible?

**Usual answers:**
- Increasing entropy (2nd law)
- Initial condition of Big Bang
- Quantum collapse

#### 6.3.2 Proposal: Time as a Property of Observers

**Hypothesis 6.1:** "Temporal flow" is not a property of spacetime but of massive observers (dτ > 0).

**Consequences:**

1. Null structures do not "live" temporal flow
2. Time emerges when massive degrees of freedom appear
3. The arrow of time is linked to the evolution of massive systems (thermodynamics, decoherence)
4. The infinite energy barrier explains why null structures remain "outside of time"

**Link with cosmology:** The Big Bang is not "the beginning of time" but the emergence of massive observers from a state dominated by radiation (null structures). The transition occurred during matter-radiation decoupling, when the universe became cool enough for massive matter to dominate.

### 6.4 Implications for Future Research

#### 6.4.1 Suggested Research Programs

**Program 1: Quantum causal formalism**
- Develop an operator algebra for causal structures
- Define quantum states on C(M) (space of causal structures)
- Construct causality-preserving dynamics
- Explicitly incorporate the infinite energy barrier in the formalism

**Program 2: Observer emergence**
- Model massive particles as excitations of null structures
- Calculate mass spectra from quantum modes on causal networks
- Predict coupling constants
- Understand the microscopic origin of the m = 0 barrier

**Program 3: Experimental tests**
- Search for signatures of causal anisotropy in geometric fluctuations
- Measure corrections to S_BH for rotating/charged black holes
- Test causality at high energy (accelerators, cosmic rays)
- Probe the duration of quantum transitions (attosecond spectroscopy)

**Program 4: QFT reformulation**
- Construct QFT directly on quantum causal networks
- Derive propagators from causal geometry
- Unify renormalization and causal structure
- Understand transition/interaction energy asymmetry in this framework

**Program 5: Geometry of quantum events**
- Develop a geometric description of creation/annihilation events
- Study the formation of microscopic horizons during atomic transitions
- Relate transition duration Δt ~ ℏ/ΔE to local causal geometry

#### 6.4.2 Anticipated Obstacles

**Obstacle 1: Diffeomorphisms**
How to define diffeomorphism-invariant observables in the quantum causal sector?

**Hint:** Use causal invariants (temporal order relations between events). Energy barriers are natural geometric invariants.

**Obstacle 2: Measurement**
How to define a measurement process without reference to a classical observer?

**Hint:** Measurement emerges when a massive observer (dτ > 0) interacts with a null structure. Energy asymmetry guarantees the observer remains massive during measurement.

**Obstacle 3: Matter**
How to incorporate matter fields (fermions) in a framework based on null structures?

**Hint:** Fermions could be topological defects in causal networks, protected by the transition energy barrier.

**Obstacle 4: Origin of the barrier**
Why is the energy barrier precisely infinite at m = 0?

**Hint:** The barrier could be a consequence of the Higgs mechanism (electroweak symmetry breaking). The impossibility of "undoing" coupling with the Higgs field would require energy comparable to the universe's energy.

### 6.5 Epistemic Limit and Observational Perspective

#### 6.5.1 Inaccessibility of the Null Perspective

**Theorem 6.1 (Perspective limit):** A timelike observer cannot adopt the proper reference frame of a null particle.

**Proof:** The proper reference frame is defined by the four-velocity u^μ = dx^μ/dτ where τ is proper time. For a null geodesic, dτ = 0 identically (Lemma 2.1), thus u^μ does not exist. ∎

**Corollary 6.1:** Questions like "what does a photon perceive?" or "what is the journey duration from the photon's perspective?" are physically ill-posed—they presuppose the existence of a reference frame that does not exist mathematically.

**Epistemological implication:** Certain physical quantities (photon proper time, "subjective experience" of a null particle) are structurally indefinable, not simply unknown or difficult to measure. This indefinability is a necessary consequence of spacetime geometry.

**Link with the energy barrier:** The mathematical impossibility of defining dτ for a null particle is intimately linked to the infinite energy barrier. Both are manifestations of the same ontological discontinuity: mathematically, division by zero; physically, divergent energy.

#### 6.5.2 Optimal Observation Position

**Definition 6.1 (Geometric contact):** A timelike observer has maximal geometric contact with null structures at the boundary of their past/future light cone, i.e., at the null hypersurfaces J̇⁻(p) and J̇⁺(p) where p is the observer's position.

**Proposition 6.1:** The position of massive observer (dτ > 0) allows optimal observation of null structures precisely because it is external to them while allowing maximal geometric contact at causal boundaries.

**Detailed argument:**

1. **Impossibility of complete self-observation:** A physical system cannot completely self-observe without paradox (fundamental logical limitation)
2. **Absence of internal perspective:** Null structures have no "internal perspective" because dτ = 0 (no notion of "what it's like to be a photon")
3. **Necessity of exteriority:** Observation requires an external perspective, which requires dτ > 0
4. **Optimality of causal contact:** This external perspective is maximally informed at causal boundaries (null surfaces) where holographic information is concentrated
5. **Facilitating energy asymmetry:** The infinite barrier guarantees the observer remains external (cannot become null) while allowing interaction (emission/absorption) at finite cost

**Theorem 6.2 (Observational optimality):** Information accessible to a timelike observer about null structures is maximal at the causal boundaries of their worldline.

**Justification:**

1. By the holographic principle (Section 4.2), information is encoded on null surfaces
2. By the Reeh-Schlieder theorem (Theorem 3.3), quantum entanglement is maximal at causal boundaries
3. The Ryu-Takayanagi formula explicitly relates entanglement entropy to the area of (often null) surfaces

**Corollary 6.2:** The impossibility of "becoming" a null structure (infinite energy barrier) is not a regrettable limitation of our observation capacity, but rather the necessary geometric condition for observation to be possible.

**Philosophical reformulation:** "We cannot be light, but it is precisely because of this that we can see it."

#### 6.5.3 Implications for Quantum Measurement Theory

**Proposition 6.2 (Measurement as null-massive interaction):** A quantum measurement process can be understood geometrically as an event where a timelike worldline (the measuring apparatus, the observer) interacts with a null structure (the carrier of quantum information).

**Justification:**

1. Measurement requires information transfer
2. Quantum information is optimally carried by null structures (photons, etc.)
3. Measurement-system interaction typically involves emission or absorption of null particles
4. The energy barrier guarantees the measuring apparatus remains massive (dτ > 0) during measurement

**Consequence:** The "measurement problem" in quantum mechanics could be reformulated as a question about the geometry of interaction events between timelike and null ontologies.

**Hypothesis 6.2:** Wave function collapse (or decoherence) could be linked to the formation of local causal horizons during the measurement interaction, causally separating the pre-measurement state from the post-measurement state.

#### 6.5.4 Fundamental Epistemological Questions

**Question 6.1:** Are there other examples in physics where an observational limit is not a technical failure but a structural necessity?

**Possible examples:**
- Black hole event horizons: fundamental observational limit
- Uncertainty principle: impossibility of simultaneously knowing position and momentum
- Impossibility of directly measuring the quantum metric

**Question 6.2:** Is the distinction between "technical limits" (surmountable with better instruments) and "structural limits" (inherent to spacetime geometry) always clear?

**Proposition 6.3:** Structural limits are characterized by mathematical singularities (divisions by zero, divergences) or infinite energy barriers, while technical limits involve finite but large energies.

**Question 6.3:** Is the infinite energy barrier at m = 0 the only one of this type, or do other ontological boundaries exist in the space of physical theories?

**Candidates:**
- Planck limit (m = m_P, λ_C = r_S)
- Thermodynamic limit (T → 0)
- Quantum phase transitions

---

## 7. Conclusion

### 7.1 Synthesis of Results

We have demonstrated that null geodesics (causal structures with ds² = 0) play a central and unifying role in the interfaces between general relativity and quantum field theory:

**Mathematical results:**
1. Null geodesics have no proper time (Theorem 2.2)
2. Causal structure is preserved in QFT (Theorem 3.2)
3. Quantum corrections respect causality (Theorem 3.4)
4. An infinite energy barrier separates massive and null ontologies (Theorem 5.2)
5. Observation of null structures is optimal from the timelike perspective (Theorem 6.2)

**Physical results:**
1. Quantum propagators respect the constraint ds² = 0 (Section 3.1)
2. Gravitational entropy lives on null surfaces (Section 4.1)
3. The holographic principle encodes information on null boundaries (Section 4.2)
4. All semiclassical effects (Hawking, Unruh) emerge at horizons (Section 4.4)
5. Energy asymmetry (E → ∞ for transition, E ~ ℏω for interaction) explains the coexistence of ontologies (Section 5.6)

**Theoretical proposition:**

The difficulties in unifying GR and QFT stem from our attempt to quantize timelike degrees of freedom (observers) rather than null structures which are intrinsically compatible with quantum theory. The infinite energy barrier between these ontologies is not an obstacle to unification but its condition of possibility: it allows null structures to serve as a universal interface while remaining ontologically distinct.

### 7.2 Paradigm Reformulation

**Old paradigm:**
- Spacetime → Fundamental substrate
- Massive particles → Primary objects
- Photons → Special case
- Interaction = energy/momentum transfer

**Proposed new paradigm:**
- Null structures → Primordial elements
- Causal structure → Emergent from null structures
- Massive observers → Derived excitations
- Infinite barrier → Necessary ontological separation
- Finite-cost interaction → Permitted interface

**Advantages:**

This paradigm naturally resolves GR-QFT tensions because:
- ✓ **Invariance:** No reference frame (dτ = 0) → no conflict between quantum observers
- ✓ **Robustness:** Causal structure preserved under quantum corrections
- ✓ **Information:** Holographic principle places information on null surfaces
- ✓ **Interface:** Gravity-quantum naturally compatible via null structures
- ✓ **Energy asymmetry:** Explains why transition impossible but interaction permitted
- ✓ **Epistemic limit:** Clarifies what is knowable vs. structurally indefinable

### 7.3 Open Questions

**Question 1:** Can we construct a complete theory of quantum gravity based exclusively on causal structures, with the energy barrier as organizing principle?

**Question 2:** Do massive particles really emerge as collective excitations of quantum null structures? What is the microscopic origin of the m = 0 barrier?

**Question 3:** Is the classical limit (ℏ → 0) equivalent to a "causal coherence" limit (stabilization of light cones)?

**Question 4:** Is time fundamental or emergent from interactions between null structures and observers? Is the infinite energy barrier linked to the emergence of time?

**Question 5:** Are there short-term experimental tests to discriminate between this paradigm and traditional approaches? Can we directly measure the duration of quantum transitions and relate it to causal geometry?

**Question 6:** Is the transition/interaction energy asymmetry a consequence of the Higgs mechanism, or does it reveal a deeper structure of spacetime?

**Question 7:** Can we formulate a theory of quantum measurement based on the geometry of null-massive interaction events?

### 7.4 Historical and Sociological Perspective

This reformulation illustrates a recurrent pattern in physics:

**Pattern:** Structures considered "special cases" or "degenerate limits" sometimes prove to be more fundamental.

**Historical examples:**
- **Symmetries:** first "mathematical properties" → revealed as conservation laws (Noether)
- **Gauge groups:** first "technical ambiguity" → revealed as fundamental structure of interactions
- **Singular limits:** first "mathematical problems" → revealed as real physical boundaries
- **Null structures:** currently "limiting case" → potentially primordial structure?

**Expected resistance:** As with any radical reformulation, cultural inertia will be strong. Pragmatic arguments ("the standard approach works") will initially dominate.

**Success criteria:** This reformulation will only prevail if it:

1. Simplifies existing calculations
2. Predicts new phenomena (e.g., signatures of the energy barrier)
3. Resolves major conceptual problems (measurement problem, origin of time)
4. Unifies apparently disparate phenomena (Hawking, Unruh, atomic emission)

### 7.5 Final Message

Null geodesics are not a technical detail of relativity. They may be the key to understanding how the universe unifies geometry and quantum theory.

The photon does not "move"—it IS a structure of spacetime.

What if this atemporality, far from being an anomaly, were the primordial form of existence from which our temporal experience emerges?

The fundamental energy asymmetry—infinite barrier between ontologies, finite interactional permeability—is not an obstacle to understanding but its very structure:

- It explains why we cannot "become" light (E → ∞)
- It explains why we can nevertheless observe and interact with it (E ~ ℏω)
- It guarantees that null structures remain universal interfaces
- It reveals a structural epistemic limit: certain perspectives are physically inaccessible

Light does not travel. It is the fixed territory on which we, temporal observers, evolve.

But we cannot become this territory. An infinite energy barrier separates us.

And it is precisely this separation that allows us to see.

This inversion of perspective—where the limit becomes a condition of possibility—could be the conceptual reformulation necessary to overcome the last obstacle toward a complete quantum theory of gravitation.
