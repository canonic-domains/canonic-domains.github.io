# COVERAGE — DOMAINS

---

## DETROS Dimensional Coverage

| Dim | Implementation | Status |
|-----|----------------|--------|
| D | CANON.md | ✓ FULL |
| E | Evidence sources | ✓ FULL |
| T | git timestamps | ✓ FULL |
| R | MED → ONCO → MAMMO | ✓ FULL |
| O | Query endpoints | ✓ FULL |
| S | Flat structure | ✓ FULL |

**DETROS Score: 6/6 (100%)**

---

## Evidence Source Coverage

### Pan-MED

| Source | Authority | URL | Status |
|--------|-----------|-----|--------|
| SNOMED | IHTSDO | snomed.org | ✓ |
| ICD | WHO | who.int | ✓ |
| LOINC | Regenstrief | loinc.org | ✓ |
| RXNORM | NLM | nlm.nih.gov | ✓ |
| CPT | AMA | ama-assn.org | ✓ |

### Oncology

| Source | Authority | Status |
|--------|-----------|--------|
| mCODE | HL7 | ✓ |
| TNM | AJCC | ✓ |
| HGVS | HVS | ✓ |

### Mammography

| Source | Authority | Status |
|--------|-----------|--------|
| NCCN | NCCN | ✓ |
| BIRADS | ACR | ✓ |

---

## Domain Hierarchy Coverage

```
DOMAINS/
├── MED/           ✓ CANON.md
│   ├── ONCO/      ✓ CANON.md
│   │   └── MAMMO/ ✓ CANON.md
│   └── EVIDENCE/  ✓ Sources
└── CANON.md       ✓ Root
```

---

*COVERAGE | Audit | DOMAINS*
