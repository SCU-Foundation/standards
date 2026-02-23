# SCU Foundation — Governance Model

This document describes the governance structure for the SCU Foundation Standards Repository.  
It defines the roles, responsibilities, and processes that ensure neutrality, stability, and long‑term stewardship of the Lattice standards ecosystem.

---

## Governance Bodies

### SCU Foundation (Steward)
The SCU Foundation is the neutral, non‑commercial governance root responsible for:

- maintaining canonical standards  
- managing versions and releases  
- ensuring long‑term stability and neutrality  
- overseeing the Standards Registry  
- approving normative changes  
- publishing official editions (HTML, PDF, GitHub)  

The Foundation does **not** develop proprietary implementations.

---

### Lattice Research Institute (LRI)
The LRI is the independent research body responsible for:

- semantic evolution  
- interpretability research  
- standards‑adjacent proposals  
- reviewing normative implications of changes  
- advising on cross‑standard consistency  

The LRI does **not** govern standards.

---

## Standards Lifecycle

### Draft → v1.0 → Subsequent Editions

1. **Draft Stage**  
   - Non‑normative  
   - Contains `README.md` and `DRAFT.md` only  
   - No versioning or changelog

2. **v1.0 Release**  
   - First normative edition  
   - Requires governance approval  
   - Gains `STATUS.md`, `VERSION`, `CHANGELOG.md`, and `LICENSE`

3. **Future Editions (v1.x, v2.x)**  
   - MUST follow the Change‑Management Process  
   - MUST document compatibility guarantees  
   - MUST update the Standards Registry

---

## Change‑Management Process

All normative changes MUST follow this process:

1. **Proposal Submission**  
   Via GitHub Issue or Pull Request.

2. **Initial Review**  
   SCU Foundation checks structure, clarity, and governance alignment.

3. **Research Review (LRI)**  
   LRI evaluates semantic and interpretability implications.

4. **Governance Decision**  
   - Approve  
   - Request revisions  
   - Reject  
   - Defer to future edition

5. **Versioning**  
   Approved normative changes MUST increment the version number.

6. **Publication**  
   Updated HTML, PDF, and GitHub editions are published.

---

## Standards Registry

The SCU Foundation maintains a canonical registry of:

- all standards  
- their versions  
- their statuses  
- their canonical locations  
- their governance metadata  

The registry is the source of truth for the ecosystem.

---

## Neutrality Requirements

All standards MUST:

- remain implementation‑agnostic  
- avoid proprietary dependencies  
- avoid commercial bias  
- preserve long‑term interoperability  

---

## Contact

For governance inquiries:  
https://scu.foundation
