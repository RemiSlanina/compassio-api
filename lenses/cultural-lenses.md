# Cultural Lenses

## 🌿 Cultural Lenses in Compassio

Compassio is designed to support a wide range of ethical worldviews — not to enforce a single one. We believe ethical clarity can emerge through respectful plurality, not dominance.

This document describes the importance of cultural lenses in shaping ethical decisions, and how to contribute new ones to Compassio.

---

## ✨ What Is a Cultural Lens?

A cultural lens is a perspective shaped by history, worldview, values, spirituality, social structure, and ways of knowing. It influences how we:

- define harm and healing
- understand dignity and justice
- relate to other beings (human, animal, river, machine)
- make decisions for the future

---

## 🌍 The Author's Lens&#x20;

The initial design of Compassio was created through a **Central European, post-industrial lens** — one shaped by values such as:

- Care ethics and dignity
- Post-war moral reflection
- Ecological and anti-authoritarian concerns
- Exposure to technocentric, rationalist culture
- A longing for more-than-human respect and spiritual humility

This is one lens among many. It carries strengths, but also limitations.

> _"This is the author’s lens — happy to expand, happy to adapt, and deeply open to contributions rooted in other worldviews."_

You are warmly invited to bring your own lens, especially if your ethics are shaped by Indigenous, spiritual, non-Western, marginalized, or place-based traditions. You do not need to "translate" your worldview into ours. We will try to meet you where you are.

---

## 🤲 How to Add a Lens

You can add a cultural lens by describing:

- `lens`: A short name or reference (e.g., `european` in my case, but others are welcome, f.e. `karma`, `ubuntu`)
- `culturalOrigin`: A few words about its source or tradition
- `values`: Key ethical principles or concerns
- `scope`: Who or what it includes as ethically relevant beings
- `weighting`: Optional. If some beings or harms are weighted more strongly
- `notes`: Anything else, including worldview context or how decisions are made

### 🌱 Example Format:

```json
{
  "lens": "ubuntu",
  "culturalOrigin": "Southern African philosophy",
  "values": ["relational dignity", "healing over punishment"],
  "scope": "human and community ecosystems",
  "weighting": { "relational harm": 0.7, "individual pain": 0.3 },
  "notes": "Ethic of interconnectedness: 'I am because we are'"
}
```

All lenses must still respect Compassio's core purpose: **to reduce suffering and uphold dignity** across beings.

---

## 🛡️ Red Lines and Ethical Boundaries

Compassio welcomes a wide range of ethical views. However, it does not support lenses that:

- Justify cruelty, torture, or systemic abuse
- Promote domination or degradation of beings
- Deny dignity based on gender, ability, ethnicity, or species
- Encourage large-scale ecological collapse

This is not to enforce sameness, but to preserve the **conditions for ethical diversity**.

---

## 🐾 Who Speaks for the Silent?

Many affected beings — animals, forests, future generations — cannot speak. Yet they deserve ethical presence.

Compassio encourages users to:

- Include non-human stakeholders using the `scope` and `consultStakeholders()` features
- Use symbolic, representative, or spiritual means of listening
- Apply dignity-preserving lenses like the `sparksLens` for beings at risk of erasure

If you speak _for_ others, do so with care.

---

## 🤝 Final Words

This is an invitation, not a final structure. Compassio longs to become more than it is.

You are welcome here.

If your tradition, culture, or ethics are missing: add them.
If you see harm: name it.
If you carry care: share it.

Plurality is not a risk to ethics. It is a form of it.

---

_This document will grow as we do._
