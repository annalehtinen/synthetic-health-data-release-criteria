# Data for: Synthetic versions of open health datasets: Success criteria and license checks for releases with a real user

This repository holds the data supplement of the working paper "Synthetic versions of open health datasets: Success criteria and license checks for releases with a real user" by Anna Lehtinen, deposited on Zenodo: https://doi.org/10.5281/zenodo.23144456 . Every file here is byte-identical to its copy in the Zenodo record; the SHA-256 of each file is listed in `MIRROR_MANIFEST.json`.

## About the paper

Where clinical records are closed, synthetic copies can give researchers usable data while protecting patient privacy. However, when the original is open, a synthetic copy offers no access advantage, and its value depends on whether anyone would download it instead of, or alongside, the original. In this study, we examine seven planned outputs that simulated reviewers or a prior-art search rejected: synthetic versions of five open health datasets, including MIMIC-IV-ECG, Sleep-EDF and VitalDB, a synthetic grid-outage set and a companion paper. Our analysis reveals a shared defect in the success criteria: four of the five health plans defined success as a synthetic-trained model coming within a margin or fraction of a real-trained one, and the fifth had no utility test against real training, so each could succeed while worse than the original. Furthermore, three health plans carried license traps: a non-commercial custodian agreement with a non-disclosure clause while the same custodian's PhysioNet release stated CC BY 4.0, a public subset with 95.3 percent of subjects under a data use agreement, and generator weights conditioned on credentialed clinical fields. We provide each candidate's success criterion and rejection reason, and seven checks for synthetic releases, such as beating real-only training on a held-out site and reading the custodian's agreement, not the mirror's license. Where the real data are open, researchers need synthetic releases tested against what a user would otherwise have.

## Files

| file | bytes |
|---|---|
| synthetic_kills.csv | 3,763 |
| synthetic_kills_counts.json | 785 |

## Not in this repository

2 file(s) of the supplement are code or logs; they are in the Zenodo record only (listed in `MIRROR_MANIFEST.json`).

## How to cite

Cite the paper: Anna Lehtinen (2026). Synthetic versions of open health datasets: Success criteria and license checks for releases with a real user. Zenodo. https://doi.org/10.5281/zenodo.23144456 . `CITATION.cff` gives the same citation (GitHub shows it under "Cite this repository").

## Licence

Creative Commons Attribution 4.0 International (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/ .
