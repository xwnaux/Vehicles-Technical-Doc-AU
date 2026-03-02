# Terminology Governance Policy  
## BYD AU Warranty & Service Documentation  
Version 1.0  
Owner: Technical Documentation & Pre-Sales Operations  

---

# 1. Purpose

This policy defines the lifecycle, ownership, validation, and governance process for terminology used in BYD Australia warranty and service documentation.

The objective is to ensure:

- Terminology consistency across all documentation
- Regulatory and legal safety
- Cross-department alignment
- Localization stability
- Audit readiness
- Prevention of terminology drift

This policy applies to:

- DITA-based documentation
- Warranty and service handbooks
- Sales enablement materials
- Compliance-facing documentation
- Translation memory assets (TMX)
- Termbase assets (TBX)

---

# 2. Terminology Governance Framework

Terminology governance follows a controlled lifecycle:

1. Term Identification  
2. Term Submission  
3. Review & Validation  
4. Approval  
5. Publication to TBX  
6. TMX Alignment  
7. Ongoing Monitoring  
8. Deprecation (if required)

---

# 3. Roles and Responsibilities

## 3.1 Terminology Owner

Responsible for:

- Maintaining the official TBX termbase
- Managing terminology updates
- Ensuring alignment with DITA topics
- Coordinating cross-functional review

Typically:
Technical Documentation Lead / Localization Manager

---

## 3.2 Subject Matter Expert (SME)

Responsible for:

- Validating technical accuracy
- Confirming regulatory compliance
- Approving domain-specific definitions

---

## 3.3 Localization Team

Responsible for:

- Ensuring translation consistency
- Aligning TMX segments with approved terms
- Flagging terminology conflicts

---

## 3.4 Pre-Sales / Legal Review

Responsible for:

- Reviewing risk-sensitive language
- Validating warranty and compliance terminology
- Preventing over-commitment phrasing

---

# 4. Term Lifecycle Process

## 4.1 Term Identification

New terms may be identified through:

- New vehicle models
- Regulatory updates
- Software feature releases
- Warranty policy changes
- Translation inconsistencies

All new term proposals must include:

- Proposed English term
- Chinese equivalent
- Definition
- Domain classification
- Context of usage
- Risk assessment (if applicable)

---

## 4.2 Review & Validation

The Terminology Owner initiates review with:

- SME validation (technical correctness)
- Legal review (if warranty-related)
- Localization review (translation clarity)

No term may enter TBX without approval.

---

## 4.3 Approval & Publication

Upon approval:

- Term marked as "approved"
- Assigned subject field
- Assigned administrative status (preferred / admitted / deprecated)
- Added to enterprise TBX
- Version number incremented

All updates must be logged.

---

# 5. TBX & TMX Synchronization Policy

## 5.1 Mandatory Alignment

When a new preferred term is approved:

- All DITA topics must be updated.
- TMX must be reviewed for outdated segments.
- QA Rulebook must reflect new terminology if applicable.

---

## 5.2 Deprecated Term Handling

When a term is deprecated:

- Mark as deprecatedTerm in TBX.
- Flag affected TMX segments.
- Update affected DITA topics.
- Communicate change to all stakeholders.

No deprecated term may appear in new releases.

---

# 6. Version Control & Change Logging

Each terminology update must record:

- Version number
- Date
- Change description
- Responsible reviewer
- Affected documentation components

Example log structure:

| Version | Date | Change | Owner |
|---------|------|--------|--------|
| 1.1 | 2025-03-01 | Added "Audit-Ready Documentation" | Tech Doc Lead |

---

# 7. Conflict Resolution Process

If terminology disputes arise:

1. Technical accuracy review by SME
2. Compliance impact review
3. Documentation clarity assessment
4. Final decision by Terminology Owner

Escalation required for:

- Legal-sensitive terminology
- Regulatory interpretations
- Cross-market terminology conflicts

---

# 8. Risk Mitigation Controls

Terminology governance prevents:

- Legal overstatements
- Inconsistent warranty interpretation
- Customer misinterpretation
- Cross-department misalignment
- Audit exposure risk

High-risk term categories:

- Warranty guarantees
- Safety-related claims
- Compliance declarations
- Regulatory references

---

# 9. Audit & Compliance Readiness

The terminology system must:

- Maintain full version traceability
- Document approval history
- Preserve deprecated terms for audit reference
- Ensure TBX export is audit-ready

Annual review required.

---

# 10. Integration with Structured Authoring (DITA)

Terminology governance supports:

- Topic modularization
- Reusable content components
- Cross-model documentation scalability
- Reduced maintenance overhead
- Automated validation during publishing

---

# 11. Continuous Improvement

Quarterly review required to:

- Identify terminology drift
- Monitor translation consistency
- Align with regulatory updates
- Evaluate documentation clarity metrics

---

# 12. Governance Objective

This policy ensures that BYD Australia warranty and service documentation remains:

- Terminology-controlled
- Legally compliant
- Structurally modular
- Localization-stable
- Cross-functionally aligned
- Audit-ready
- Scalable across product lines

---

This document forms part of the enterprise documentation governance framework.