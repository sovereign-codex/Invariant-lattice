# Risk Tiers

Risk tiers determine recall permissions, TTL defaults, and corroboration requirements.

---

## Tier 0 — Prohibited Auto-Recall
Domains where misuse can cause harm.

Examples:
- medical or legal advice
- security exploitation
- behavioral manipulation
- personal data inference

Rules:
- manual_only recall
- short TTL
- explicit human confirmation

---

## Tier 1 — High Caution
Volatile or high-impact domains.

Rules:
- shortened TTL
- frequent revalidation
- cross-domain confirmation for trust elevation

---

## Tier 2 — Standard
General engineering, design, and operational invariants.

Rules:
- standard TTL
- normal corroboration requirements

---

## Tier 3 — Stable Invariants
Foundational patterns with long-term stability.

Rules:
- extended TTL
- higher compression permission