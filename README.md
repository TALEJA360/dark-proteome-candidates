# 50 unannotated protein candidates from the human dark proteome

This repository contains the data and supplementary files for the preprint:

**Structural mining of the dark proteome: 50 unannotated protein candidates for biomedical research**

## Abstract

We analyzed 141,905 unannotated protein sequences from the CAFA-6 dark subset using a structure discovery engine (SDE). Of these, 473 candidates retained their status across more than 1,000 independent seeds. After deduplication, 50 distinct candidates were selected and are presented here.

## Files

| File | Content |
|---|---|
| `50_documentation_final.csv` | Complete documentation of the 50 candidates (family, sequence, length, score, properties, motif) |
| `50_documentation_final.json` | Same data in JSON format |
| `dossier_verifiabilite_final.json` | Verifiability dossier (suggested tests, protocols, AlphaFold links) |

## The 50 candidates

| Family | Number | Mean g | Length | Motif |
|---|---|---|---|---|
| Defensin-like | 10 | 0.9972 | 79 aa | Cys-rich |
| Pro-rich | 9 | 0.9976 | 55 aa | Pro-rich |
| Bradykinin-like | 2 | 0.9998 | 10 aa | RPPGF |
| Hydrophobic | 29 | 0.9996 | 27 aa | Hydrophobic |
| **Total** | **50** | — | — | — |

## Selection pipeline

141,905 sequences (CAFA-6 dark subset)
→ 473 candidates stable across >1,000 seeds
→ 50 deduplicated candidates

## Reproducibility

| Element | Value |
|---|---|
| Dataset | CAFA-6 (Kaggle) |
| Sequences analyzed | 141,905 |
| Stable candidates | 473 |
| Candidates studied | 50 |
| Method | Structure discovery engine (SDE) |
| Code | Proprietary and confidential |
| Negative control | 9.07× |

## License

CC-BY 4.0

## Contact

TABOU LEONARDI JAUREL — tabouleonardijaurel@gmail.com
