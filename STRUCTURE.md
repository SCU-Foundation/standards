# SCU Foundation Standards Repository — Structure Overview

This document provides a canonical overview of the folder and file structure used in the SCU Foundation Standards Repository.  
It ensures consistency, clarity, and long‑term maintainability across all standards.

---

## Root Structure

```
/standards
    /ts
    /lp
    /lw
    /lm
    /lit
CONTRIBUTING.md
GOVERNANCE.md
CODE_OF_CONDUCT.md
STRUCTURE.md
LICENSE
README.md
```

---

## Standards Folder Structure

Each standard lives in its own folder under `/standards/<standard>/`.

### Example (TS v1.0):

```
/standards/ts
    README.md
    TS-v1.0.md
    STATUS.md
    VERSION
    CHANGELOG.md
    LICENSE
```

### Required Files

**README.md**  
Overview of the standard, canonical links, governance, and conformance.

**<STANDARD>-vX.Y.md**  
The full normative specification.

**STATUS.md**  
Status, version, steward, research body, canonical links.

**VERSION**  
Single-line version identifier (e.g., `v1.0`).

**CHANGELOG.md**  
Version history and release notes.

**LICENSE**  
CC‑BY‑4.0 license for the standard.

---

## Draft Standards Structure

Draft standards follow the same folder pattern but contain placeholder files:

```
/standards/<standard>
    README.md
    DRAFT.md
```

Drafts MUST NOT include:

- VERSION  
- CHANGELOG  
- STATUS  
- LICENSE  

until they reach v1.0.

---

## Governance & Contribution Files

**CONTRIBUTING.md**  
Defines how proposals, issues, and changes must be submitted.

**GOVERNANCE.md**  
Outlines the SCU Foundation governance model, roles, and change‑management process.

**CODE_OF_CONDUCT.md**  
Required for public repositories; ensures safe and respectful participation.

**STRUCTURE.md**  
This file — canonical overview of the repository structure.

**LICENSE**  
Root license for the entire repository (CC‑BY‑4.0 recommended).

---

## GitHub Workflow Templates

Located under:

```
/.github
    ISSUE_TEMPLATE.md
    PULL_REQUEST_TEMPLATE.md
```

These templates ensure all contributions follow standards‑body discipline.

---

## Summary

This structure ensures:

- clarity for contributors  
- consistency across standards  
- alignment with SCU Foundation governance  
- future‑proofing for new standards and versions  
- institutional maturity comparable to W3C, IETF, and ISO  

All new standards MUST follow this structure.
