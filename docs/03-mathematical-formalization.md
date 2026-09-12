# 03 — Mathematical Formalization v0.2 / Formalisasi Matematis v0.2

> **Status:** provisional mathematical scaffolding. These expressions organize PSESH; they are not established laws of physics.

## 1. Symbols / Simbol

| Symbol | Meaning |
|---|---|
| `P` | Primordial Substance |
| `C_P` | primordial consciousness |
| `W_P` | primordial will / kehendak primordial |
| `Σ_n` | model state at logical/computational ordering index `n` |
| `D` | differentiation operator: rule for one state transition |
| `G` | generative law/mapping: broader law producing an emergent history/structure |
| `λ_W` | coupling parameter between primordial will and differentiation |
| `R_n` | relational structure |
| `S,T` | emergent spatial and temporal structure |
| `g` | emergent geometry/metric |
| `E_phys` | physical energy in the emergent physical regime |
| `M` | matter/fields/physical degrees of freedom |
| `C_i` | individual consciousness |
| `Ω_i` | organized physical/informational structure associated with individual `i` |
| `Λ` | other unknown lawful parameters |

## 2. Ontological foundation / Fondasi ontologis

**[PSESH]**

\[
\operatorname{Exists}(P)=1
\]

This is an existence predicate, not a claim that P is literally a set, field, manifold, or ordinary physical substance.

Relative absence is represented by

\[
N(X\mid F)=1,
\]

meaning X is absent relative to frame/domain F. This does not imply an instantiated state of absolute non-being.

## 3. Primordial intrinsic structure

PSESH presently treats consciousness and will as intrinsic aspects of P rather than later products:

\[
C_P\in\operatorname{Intrinsic}(P),
\qquad
W_P\in\operatorname{Intrinsic}(P).
\]

A compact primordial state notation is therefore

\[
\Sigma_P=(P,C_P,W_P,\Lambda).
\]

The components in this tuple are explanatory/formal distinctions. They do not imply that P, consciousness, and will were temporally assembled in sequence.

Physical energy remains distinct:

\[
E_{\mathrm{phys}}\neq C_P,
\qquad
E_{\mathrm{phys}}\neq W_P.
\]

Ordinary physical energy is introduced only after an emergent physical regime exists.

## 4. `D` and `G`

`D` and `G` are not additional substances.

**`D` — differentiation operator** describes a local/stepwise transition:

\[
\Sigma_{n+1}=D(\Sigma_n;P,C_P,W_P,\Lambda).
\]

**`G` — generative law** denotes the broader mapping that produces an emergent sequence or structure:

\[
\mathcal H=G[P,C_P,W_P;\Lambda],
\]

where `𝓗` is a generated history/ordered family of states in the model. The index `n` and the ordering in `𝓗` are logical/computational unless physical time has already emerged.

## 5. Primordial Will Causation Hypothesis

**[PSESH][SPEC]** Current causal hypothesis:

> Primordial differentiation is initiated, selected, or constrained by primordial will.

The important distinction is between **existence of will** and **causal coupling of will to differentiation**. PSESH does not need to remove `W_P` from ontology to construct a control model.

Define a coupling parameter:

\[
\Sigma_{n+1}=D(\Sigma_n;P,C_P,\lambda_W W_P,\Lambda).
\]

Two matched models can then be compared:

\[
M_0:\;\lambda_W=0
\]

will exists as an intrinsic aspect of P but has no causal coupling to differentiation, versus

\[
M_1:\;\lambda_W\neq0
\]

where primordial will changes or constrains state transitions.

The minimal causal relevance condition is

\[
D(\Sigma;\lambda_W\neq0)\neq D(\Sigma;\lambda_W=0)
\]

for at least some admissible states/conditions.

This is a **research criterion**, not evidence that the criterion is satisfied in nature.

## 6. Will as constraint/selection

A minimally committed formal interpretation is:

\[
W_P:\mathcal A(\Sigma_n)\rightarrow \text{constraint or preference over admissible }\Sigma_{n+1},
\]

where `𝒜(Σ_n)` denotes possible next states allowed by the rest of the model.

A stochastic form may later compare

\[
K_W(\Sigma'\mid\Sigma,W_P)
\]

with

\[
K_0(\Sigma'\mid\Sigma).
\]

Causal relevance requires that these transition structures differ under controlled assumptions. PSESH does not yet specify the selection criterion, objective, or probability law.

## 7. Differentiation measure

A candidate differentiation functional may later be defined:

\[
\Delta_n=\operatorname{Diff}(\Sigma_n).
\]

No definition of `Diff` has yet been selected. Monotonicity such as

\[
\Delta_{n+1}\geq\Delta_n
\]

must not be assumed unless derived or explicitly adopted for a particular model regime.

## 8. Emergent relations and geometry

**[SPEC]**

\[
R_n\xrightarrow{\mathcal E}(M,g).
\]

Candidate mathematical tools for relational emergence may include

\[
d_G(i,j)=\min_{p:i\to j}|p|
\]

and effective dimensional scaling

\[
N(r)\propto r^{d_{\mathrm{eff}}},
\qquad
d_{\mathrm{eff}}\approx\frac{d\ln N(r)}{d\ln r}.
\]

These are candidate tools, not established PSESH laws.

## 9. Physical regime

Only after a physical/spatiotemporal regime has emerged do ordinary physical quantities become safely applicable:

\[
(M,g)\Rightarrow E_{\mathrm{phys}},\;\text{fields},\;\text{matter},\ldots
\]

PSESH currently has no derivation of the Standard Model, Einstein field equations, quantum fields, or a specific cosmological metric.

## 10. Individual consciousness

**[SPEC][OPEN]**

\[
C_i=\mathcal I(C_P,\Omega_i).
\]

This records the individuation problem but does not solve it. `𝓘` remains unknown.

## 11. Causal model comparison

The current test program for primordial will is:

\[
M_0:(P,C_P,W_P),\;\lambda_W=0
\]

versus

\[
M_1:(P,C_P,W_P),\;\lambda_W\neq0.
\]

A future implementation can perform an ablation/counterfactual comparison while holding the remaining model assumptions fixed. A calculable functional `Q` would be needed such that

\[
Q(M_1)\neq Q(M_0)
\]

and, eventually, the difference would need to connect to a discriminating empirical consequence.

## 12. Boundary

If ordinary space is emergent,

\[
\partial P\;\text{is undefined in the present model}.
\]

If physical time is emergent, ordinary `t_start(P)` and `t_end(P)` are likewise not presently defined.

## 13. Current missing pieces

The formal program still requires: a mathematical definition of `P`; an explicit `D` and/or `G`; a formal characterization of `W_P`; a specified coupling mechanism `λ_W`; an emergence map `𝓔`; a solution or stronger model of consciousness individuation; and predictions that distinguish the causally coupled model from matched alternatives.

The question “can will exist in an undifferentiated state?” is **not treated as a prerequisite** for this program. Under current PSESH ontology, `C_P` and `W_P` are already intrinsic to P. The scientific/formal question is whether `W_P` has a non-redundant causal role in differentiation.
