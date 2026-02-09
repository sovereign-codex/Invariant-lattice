# Memory Handshake Protocol

The handshake defines how models interact with the invariant-lattice.

---

## Query Inputs
- domain_tags
- invariant_signature
- context_risk
- desired_expansion

---

## Response Outputs
- meta_hash_id
- confidence
- trust_level
- ttl_remaining
- constraints
- required_actions

---

## Feedback Loop
All consumers are expected to return feedback events.
Feedback drives decay, refinement, and collective learning.