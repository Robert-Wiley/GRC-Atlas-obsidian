---
map_type: topology_validation
baseline: pilot-001
status: active
---

# Pilot Topology Validation — GRC Mapping

## Purpose
Validate the Obsidian ↔ GitHub ↔ Atlas relational-discovery bridge before scaling the full 286-object corpus.

## Pilot objects

### Governance
- [[Governance/GOV-001 - Organizational Purpose Direction and Identity]]
- [[Governance/GOV-002 - Authority and Decision Rights]]
- [[Governance/GOV-003 - Accountability and Responsibility]]

### Risk
- [[Risk/RSK-001 - Risk Context Definition]]
- [[Risk/RSK-002 - Risk Scope Definition]]
- [[Risk/RSK-003 - Risk Objective Association]]

### Compliance
- [[Compliance/CMP-001 - Compliance Context Definition]]
- [[Compliance/CMP-002 - Compliance Scope Definition]]
- [[Compliance/CMP-003 - Jurisdiction Identification]]

## Canonical relationship layer
- [[Relationships/REL-0236 - GOV-001 informs RSK-001]]
- [[Relationships/REL-GC-0042 - GOV-001 informs CMP-001]]
- [[Relationships/REL-C2-0001 - CMP-001 informs CMP-002]]
- [[Relationships/REL-C2-0002 - CMP-001 informs CMP-003]]

## Validation questions
1. Do all nine object notes appear?
2. Do all four relationship notes appear as first-class nodes?
3. Does GOV-001 bridge Governance to both Risk and Compliance?
4. Does CMP-001 fan out to CMP-002 and CMP-003?
5. Are relationship nodes visible and navigable in Graph View?
6. Does the graph remain understandable without exposing protected analytical mechanics?

## Scale gate
If this pilot renders correctly, proceed to staged corpus expansion using canonical Notion object and relationship records.
