# Data licence

The code in this repository is released under the MIT licence (see `LICENSE`).

The data created for this study — the benchmark item selection and design
(`data/processed/`), all stored model responses (`results/`), the supplementary
tables (`supplementary/`) and the figures (`figures/`) — are released under the
[Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
Please cite the accompanying paper (see `CITATION.cff`) when reusing them.

## Third-party content

The interactions, signs and publication identifiers in the benchmark were
derived from [OmniPath](https://omnipathdb.org/) (downloaded 22 August 2026 with
the `omnipath` Python package 1.0.12, default academic licence filter). OmniPath
integrates many primary resources, and each keeps its own licence; some restrict
commercial use. Anyone reusing the OmniPath-derived parts of this repository
must comply with the licences of those original resources. The raw OmniPath
download is not redistributed here; `data/raw/snapshot_manifest.json` records
its checksums so it can be re-created and verified.

Model responses were generated through the providers listed in Supplementary
Note S2 and are shared for research purposes.
