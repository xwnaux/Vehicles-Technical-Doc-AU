# Version Control Model  
## BYD AU Warranty & Service Documentation  
Version 1.0  

---

# 1. Purpose

This document defines versioning standards for DITA topics, TBX assets, TMX memory files, and governance documentation.

---

# 2. Versioning Structure

Format:

MAJOR.MINOR.REVISION

Example:
2.3.1

---

# 3. Version Definitions

## 3.1 Major Version

Increment when:

- Warranty policy changes
- Regulatory updates
- Structural DITA changes
- Legal wording adjustments

Impact:
- Requires full review cycle

---

## 3.2 Minor Version

Increment when:

- New topics added
- Terminology updated
- Clarifications added
- Non-structural improvements made

---

## 3.3 Revision Version

Increment when:

- Typographical corrections
- Formatting adjustments
- Minor phrasing improvements

---

# 4. TBX & TMX Version Alignment

Whenever TBX version increases:

- TMX must be reviewed
- QA rules must be validated
- Impacted DITA topics updated

---

# 5. Archiving Policy

Each version must:

- Be archived
- Include release notes
- Retain change summary
- Maintain approval metadata

---

# 6. Git Strategy (Portfolio Simulation)

Recommended branching model:

- main (approved release)
- draft (in-progress work)
- feature/term-update
- hotfix/legal-update

Tag format:

release-v1.2.0

---

# 7. Audit Requirement

Version history must allow:

- Traceability of terminology changes
- Identification of approval owner
- Review of past warranty wording

---

# 8. Governance Objective

Version control ensures:

- Stability
- Transparency
- Traceability
- Risk mitigation
- Controlled scalability