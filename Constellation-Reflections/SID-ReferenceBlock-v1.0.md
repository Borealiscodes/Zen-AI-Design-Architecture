# **SID\(_\text{NDH}\) Reference Block (Canonical)**  
### *Stability Invariant Definition — Non‑recursive mathematical ceiling*

```
[📐 SID_NDH — STABILITY INVARIANT DEFINITION]

SID_NDH is the formal mathematical ceiling for all reflection‑layer artifacts
within Zen-AI-Design-Architecture. It is externally proven, machine-checked, and
non-recursive. Reflection-layer constructs may reference SID_NDH but may not
modify, extend, or redefine it.

Definition:
Let n ≥ 3. Let X = [0,1]^n. Let F : X → X be the cyclic ring consensus update
map. Let span(x) = max_i x_i − min_i x_i. Let C be the consensus set:
C = { x ∈ X | ∃ c ∈ [0,1] : x_i = c for all i }.

SID_NDH provides three invariants:

1. Forward invariance:
   F(x) ∈ X for all x ∈ X.

2. Strict span contraction:
   For all non-consensus x ∈ X:
   span(F(x)) < span(x).

3. Global consensus attraction:
   For all x ∈ X:
   lim_{k→∞} F^k(x) ∈ C.

Origin:
This invariant is grounded in a Lean 4 machine-checked anti-collapse proof
contributed by Jonathan Reed and used under the MIT License.

Constraint:
All reflection-layer documents (Safety Standard, Recursion Boundary Charter,
Roadmap, and Reflective Surfaces) must operate strictly beneath SID_NDH. No
reflection artifact may alter X, F, span, C, or the invariants above.

Purpose:
SID_NDH prevents upward recursion into governance (NDH-CORE) or computational
(SCI-80) layers and provides a mathematically closed stability ceiling for
reflection-layer emergence.
```

---

# 📜 **Provenance Footer**

```markdown
---
Provenance: The SID_NDH Reference Block v1.0 formalizes the Stability Invariant
Definition as the mathematical ceiling for reflection-grade artifacts within
Zen-AI-Design-Architecture. SID_NDH is based on a Lean 4 machine-checked
anti-collapse proof contributed by Jonathan Reed and used under the MIT License.
It establishes forward invariance, strict span contraction, and global consensus
attraction for a cyclic ring consensus protocol over [0,1]^n (n ≥ 3). Reflection
documents may reference but not alter this invariant.

Lane: Zen-AI-Design-Architecture/Constellation-Reflections • Version: v1.0 •
Maintainer: Borealis S. Hedling • Dublin, Ireland
---
```

---

