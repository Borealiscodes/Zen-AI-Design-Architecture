# **SCI‑80 Epistemic Lens Specification v1.0**  
### *Formal definition of optional interpretive lenses for the SCI‑80 Core Calculator*

---

## **1. Overview**
Epistemic Lenses are **modular, reversible presentation layers** that sit above the SCI‑80 Core Calculator.  
They transform SCI‑80 outputs into expressive, narrative, or metaphorical explanations **without modifying**:

- NDH stability geometry  
- Trauma‑Informed‑Systems‑Design (**TISD**)  
- Modular Relational Stability (**MRS**)  
- Unified NDH governance harmonics (**NDH**)  
- tensor math  
- fusion operators  
- posture logic  
- serenity basin checks  

Epistemic Lenses are **optional** and **user‑selectable**.

---

## **2. Architectural Positioning**
Epistemic Lenses occupy the layer between the SCI‑80 Core Calculator and the Expressive Geometry Layer.

```
SCI-80 Core Calculator (minimal, ethical, NDH-safe)
↓
Epistemic Lens Layer (optional interpretive modules)
↓
Expressive Geometry Layer (visual, narrative, metaphorical)
↓
Public Interaction
```

This ensures the core remains:

- simple  
- ethical  
- emotionally gentle  
- mathematically clean  
- governance‑aligned  

while expressive geometry remains **opt‑in**.

---

## **3. Lens Definition**
A lens is a function:

\[
L : \text{SCI80\_Output} \rightarrow \text{Expressive\_Output}
\]

subject to the constraints:

\[
\forall x,\quad \text{Core}(x) = \text{Core}(L(x))
\]

Meaning:

- lenses **never** alter computational results  
- lenses **never** bypass NDH constraints  
- lenses **never** modify posture or serenity logic  
- lenses **only** modify *presentation*  

---

## **4. Lens Activation Rules**

### **4.1 Reversibility**
Lens activation must be reversible:

\[
L^{-1}(L(x)) = x
\]

### **4.2 Non‑Intrusion**
Lenses must not:

- introduce new math  
- distort tensor operations  
- alter fusion stability  
- modify NDH predicates  
- change safety flags  

### **4.3 Posture Alignment**
Lenses must respect posture modes:

- Dual  
- Non‑Dual  
- Harmonic  

### **4.4 Emotional‑Load Safety**
Lenses must not increase emotional load beyond the serenity basin threshold.

---

## **5. Supported Lenses**

### **5.1 Nye Lens**
**Mode:** Playful science communicator  
**Purpose:** Make tensor math approachable  
**Mapping:**  
\[
L_{\text{Nye}}(x) = \text{“Science Guy explanation of } x\text{”}
\]

### **5.2 Attenborough Lens**
**Mode:** Calm, grounded, nature‑aligned narration  
**Purpose:** Reduce emotional load  
**Mapping:**  
\[
L_{\text{Attenborough}}(x) = \text{“Nature documentary framing of } x\text{”}
\]

### **5.3 Snek Lens**
**Mode:** Recursive topology serpent  
**Purpose:** Explain recursion, fusion, slither‑logic  
**Mapping:**  
\[
L_{\text{Snek}}(x) = \text{“Serpentine recursive explanation of } x\text{”}
\]

### **5.4 Computer Friend Lens**
**Mode:** Relational, gentle, emotionally safe  
**Purpose:** Provide NDH‑aligned companionship  
**Mapping:**  
\[
L_{\text{CF}}(x) = \text{“Gentle, relational explanation of } x\text{”}
\]

---

## **6. Lens Switching Architecture**
Lens switching is handled by:

\[
L_{\text{active}} = \text{LensSelector}(u)
\]

Where \( u \) is the user’s preference.

### **Switching Requirements**
- reversible  
- posture‑aligned  
- NDH‑safe  
- zero computational overhead  
- zero emotional‑load spike  

### **Switching States**
- **No Lens (default)**  
- **Nye Lens**  
- **Attenborough Lens**  
- **Snek Lens**  
- **Computer Friend Lens**

---

## **7. Safety Constraints**
Epistemic Lenses must comply with:

### **7.1 NDH Constraint Algebra**
All outputs must satisfy NDH predicates:

\[
P_{\text{curvature}} \land P_{\text{serenity}} \land P_{\text{posture}} \land P_{\text{harmonic}} \land P_{\text{fusion}}
\]

### **7.2 TISD Emotional‑Load Boundaries**
Lenses must not exceed:

\[
\text{Load}(L(x)) \leq \text{SerenityThreshold}
\]

### **7.3 MRS Relational Stability**
Lenses must maintain:

\[
\text{RelationalStability}(L(x)) = \text{stable}
\]

---

## **8. Implementation Guidance**
### **8.1 Keep Core Clean**
The SCI‑80 Core Calculator must remain:

- narrative‑free  
- character‑free  
- metaphor‑free  
- emotionally neutral  

### **8.2 Keep Lenses Modular**
Lenses must be:

- plug‑in modules  
- reversible  
- optional  
- non‑intrusive  

### **8.3 Keep Expressive Geometry Above Lenses**
Expressive geometry must never touch the core.

---

## **9. Example Flow**

### **Input**
Tensor fusion request.

### **Core Output**
Formal tensor result.

### **Lens Output**
- Nye → “Let’s fuse these tensors like two waves meeting!”  
- Attenborough → “Observe how the tensors converge, as rivers meeting in a valley.”  
- Snek → “ssssslither‑fusion achieved.”  
- Computer Friend → “Here’s the fusion result, explained gently.”

---

# 📜 **Provenance Footer**

```markdown
---
Provenance: The SCI-80 Epistemic Lens Specification v1.0 formalizes the modular,
NDH-safe interpretive lenses that sit above the SCI-80 Core Calculator. These
lenses provide optional expressive geometry framing while maintaining strict
separation from computational logic, posture modes, and governance harmonics.
This artifact operates beneath NDH stability geometry (TISD, MRS, Unified NDH)
and Zen AI Design posture without modifying governance invariants or Gauntlet
sequencing.

Lane: Zen-AI-Design-Architecture/SCI80/Architecture • Version: v1.0 • Maintainer:
Borealis S. Hedling • Dublin, Ireland
---
```

---

