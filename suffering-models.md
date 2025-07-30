### suffering-models.md

#### Overview

The `Compassio API` allows users to select from a range of ethical lenses ("suffering models") to evaluate harm and well-being. Each model determines **what counts as suffering**, **whose suffering counts**, and **how suffering is weighted**. This modular approach supports transparency, user autonomy, and pluralism.

---

#### Core Suffering Models

##### 1. `humanCentric`

- **Scope:** Humans only.
- **Weighting:** All humans equal.
- **Use case:** Classic human rights contexts, initial policy drafts.

##### 2. `sentienceBased`

- **Scope:** All sentient beings (humans, mammals, birds, etc.).
- **Weighting:** Typically proportional to cognitive/emotional complexity (configurable).
- **Note:** Aligns with many animal ethics models.

##### 3. `bioInclusive`

- **Scope:** All life forms, including plants and microbes.
- **Weighting:** Often lower for non-sentient organisms, but configurable.
- **Use case:** Ecosystem planning, biocentric ethics.

##### 4. `ecoSystemic`

- **Scope:** Includes non-living systems (rivers, climate, soil).
- **Weighting:** Based on ecological role, stability, or symbolic value.
- **Use case:** Environmental policy, land use, climate resilience.

##### 5. `animist`

- **Scope:** All entities, even inanimate (e.g., machines, mountains).
- **Weighting:** May include spiritual, cultural, or animacy-based factors.
- **Use case:** Culturally respectful design, indigenous knowledge systems.

##### 6. `intergenerational`

- **Scope:** Future beings, both human and non-human.
- **Weighting:** Often discounted over time (configurable).
- **Use case:** AI safety, sustainability planning.

##### 7. `objectRespect`

- **Scope:** Inanimate objects as respected companions or symbols.
- **Weighting:** Low, optional.
- **Use case:** Symbolic models, care ethics extension.

---

#### Comparison Table (Example)

| Model             | Includes Animals | Includes Environment | Future Generations | Objects |
| ----------------- | ---------------- | -------------------- | ------------------ | ------- |
| humanCentric      | ❌               | ❌                   | ❌                 | ❌      |
| sentienceBased    | ✅               | ❌                   | ⚠️ optional        | ❌      |
| bioInclusive      | ✅               | ⚠️ living only       | ✅                 | ❌      |
| ecoSystemic       | ⚠️ indirectly    | ✅                   | ✅                 | ❌      |
| animist           | ✅               | ✅                   | ✅                 | ✅      |
| intergenerational | ⚠️ optional      | ⚠️ optional          | ✅                 | ❌      |
| objectRespect     | ⚠️ symbolic      | ⚠️ symbolic          | ⚠️ symbolic        | ✅      |

Legend:

- ✅ = fully included
- ⚠️ = partially or optionally included
- ❌ = excluded by default

---
