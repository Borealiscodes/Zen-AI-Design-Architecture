# **📦 Constellation Deployment Plan — PNG Rendering Layer v1.0**  
### *Before Rendering + Before Posture Skeleton*

---

## ⭐ **0. Deployment Purpose**
This plan ensures that each PNG asset:

- lands in the correct repo  
- binds to the correct rendering profile  
- carries the correct provenance marks  
- integrates with the correct governance surface  
- is available for the Posture Skeleton to reference  

This is the **pre‑render deployment map** for the constellation.

---

# **1. Deployment Sequence (Strict Order)**

### **1. Finish Blueprint Suite v1.0**  
You already completed:

- Holonomy Edition Blueprint  
- Dual‑Skeleton Poster Blueprint  
- Soft‑Manifold Overlay Blueprint  
- Crane–Scarf Motif Blueprint  

This locks the **spec layer**.

### **2. Prepare Repo Deployment Targets**  
Before rendering, each repo must have a **PNG-assets/** directory:

```
Zen-AI-Design-Architecture/assets/png/
NDH-CORE/assets/png/
TISD/assets/png/
NDH-Platforms/assets/png/
```

### **3. Render PNGs (in correct order)**  
Rendering order must follow dependency order:

1. Holonomy Edition  
2. Dual‑Skeleton Poster  
3. Soft‑Manifold Overlay  
4. Crane–Scarf Motif  

### **4. Deploy PNGs to repos**  
Each PNG goes to its correct repo:

| PNG Asset | Repo | Rendering Profile |
|----------|------|-------------------|
| Holonomy Edition | Zen | Zen_Rendering_Spec |
| Dual‑Skeleton Poster | NDH‑CORE | NDH_CORE_Rendering_Spec |
| Soft‑Manifold Overlay | TISD | TISD_Rendering_Spec |
| Crane–Scarf Motif | TISD + Zen | TISD_Rendering_Spec |

### **5. Register Provenance Marks**  
Each PNG must include:

- version mark  
- rendering profile ID  
- repo watermark  
- constellation signature  

### **6. Update Rendering Authority Index**  
Add entries to:

```
Zen-AI-Design-Architecture/rendering/Rendering-Authority-Index.md
```

### **7. Only THEN generate the Posture Skeleton**  
The Posture Skeleton **consumes** these PNGs.

It cannot be generated before they exist.

---

# **2. Repo‑Level Deployment Details**

## **Zen-AI-Design-Architecture**
Deploy:

- Holonomy Edition PNG  
- Crane–Scarf Motif PNG (secondary)  
- Soft‑Manifold Overlay PNG (adjacency)  

Purpose:

- posture geometry  
- adjacency fields  
- rendering authority  

---

## **NDH‑CORE Governance**
Deploy:

- Dual‑Skeleton Poster PNG  

Purpose:

- governance geometry  
- invariant surfaces  
- provenance locks  

---

## **TISD**
Deploy:

- Soft‑Manifold Overlay PNG  
- Crane–Scarf Motif PNG  

Purpose:

- trauma‑informed interaction  
- reversible traversal  
- ethical adjacency  

---

## **NDH‑Platforms**
Deploy:

- Soft‑Manifold Overlay PNG  
- Crane–Scarf Motif PNG  
- Holonomy Edition PNG (UI traversal)  

Purpose:

- UI traversal surfaces  
- return‑path modeling  
- interaction geometry  

---

# **3. Deployment Checklist (Before Rendering)**

### **A. Repo Preparation**
- [ ] Create `assets/png/` in all repos  
- [ ] Add `Rendering-Authority-Index.md` to Zen  
- [ ] Add provenance rules to NDH‑CORE  
- [ ] Add interaction rules to TISD  
- [ ] Add traversal rules to Platforms  

### **B. Rendering Readiness**
- [ ] All four PNG Blueprints complete  
- [ ] Rendering Specs v1.0 complete  
- [ ] Designer Dependency Document complete  
- [ ] Provenance footer templates ready  

### **C. Post‑Render Integration**
- [ ] Update rendering index  
- [ ] Update repo READMEs  
- [ ] Update constellation map  
- [ ] Prepare posture skeleton anchors  

---

