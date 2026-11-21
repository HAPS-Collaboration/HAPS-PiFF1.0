# HAPS-PiFF1.0
Modern Determination of Charged-Pion and Charged-Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities

<p align="left">
  <img src="https://img.shields.io/badge/HAPS--PiFF1.0-Charged--Pion%20FF%20Set-2E7D32?style=for-the-badge" alt="HAPS-PiFF1.0">
</p>

# HAPS-PiFF1.0

**HAPS-PiFF1.0** is a charged-pion fragmentation-function set developed within the **HAPS Collaboration**.

The grids accompany the analysis:

> **Modern Determination of Pion and Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities**
> Maryam Soleymaninia, Hamzeh Khanpour, Hubert Spiesberger, Majid Azizi, Michael Klasen, and Hadi Hashamipour

## Paper

* **Title:** Modern Determination of Pion and Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities
* **Authors:** Maryam Soleymaninia, Hamzeh Khanpour, Hubert Spiesberger, Majid Azizi, Michael Klasen, and Hadi Hashamipour
* **Collaboration:** HAPS Collaboration
* **arXiv:** https://arxiv.org/abs/2606.16754
* **INSPIRE:** https://inspirehep.net/literature/3168717
* **DOI:** https://doi.org/10.1103/tw9g-7q7x
* **LHAPDF grids:** https://github.com/HAPS-Collaboration/HAPS-PiFF1.0

## Physics scope

HAPS-PiFF1.0 provides charged-pion fragmentation functions extracted from a global QCD analysis combining single-inclusive electron-positron annihilation data with charge-separated semi-inclusive deep-inelastic-scattering multiplicities from HERMES and COMPASS.

The analysis incorporates modern COMPASS SIDIS measurements, including the 2025 proton-target multiplicities and the 2026 revised isoscalar-target multiplicities. The revised isoscalar measurements supersede the earlier COMPASS datasets used in previous global fragmentation-function analyses.

The charge-separated pion measurements enhance the sensitivity to favored and unfavored light-quark fragmentation channels. In particular, they provide important information on the flavor structure of charged-pion production, including the favored $u \to \pi^+$ and $\bar{d} \to \pi^+$ fragmentation channels.

The extraction is performed at next-to-leading order and within a next-to-next-to-leading-order perturbative-QCD setup. The resulting Monte Carlo replica sets are provided in standard LHAPDF format.

## Available LHAPDF grids

This repository contains six charged-pion fragmentation-function sets:

| Grid directory            | Hadron combination | Perturbative order |
| ------------------------- | -----------------: | -----------------: |
| `HAPS-PiFF1.0-plus-NLO`   |                 π⁺ |                NLO |
| `HAPS-PiFF1.0-plus-NNLO`  |                 π⁺ |               NNLO |
| `HAPS-PiFF1.0-minus-NLO`  |                 π⁻ |                NLO |
| `HAPS-PiFF1.0-minus-NNLO` |                 π⁻ |               NNLO |
| `HAPS-PiFF1.0-sum-NLO`    |            π⁺ + π⁻ |                NLO |
| `HAPS-PiFF1.0-sum-NNLO`   |            π⁺ + π⁻ |               NNLO |

## Repository structure

```text
HAPS-PiFF1.0/
├── HAPS-PiFF1.0-minus-NLO/
├── HAPS-PiFF1.0-minus-NNLO/
├── HAPS-PiFF1.0-plus-NLO/
├── HAPS-PiFF1.0-plus-NNLO/
├── HAPS-PiFF1.0-sum-NLO/
├── HAPS-PiFF1.0-sum-NNLO/
└── README.md
```

## Companion charged-kaon grids

The corresponding **HAPS-KaFF1.0** charged-kaon fragmentation-function grids are available at:

https://github.com/HAPS-Collaboration/HAPS-KaFF1.0

## Citation

When using these grids, please cite:

```bibtex
%\cite{Soleymaninia:2026edd}
\bibitem{Soleymaninia:2026edd}
M.~Soleymaninia \textit{et al.} [HAPS],
%``Modern Determination of Pion and Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities,''
[arXiv:2606.16754 [hep-ph]].
%0 citations counted in INSPIRE as of 24 Jun 2026
```

## Related resources

* HAPS Collaboration: https://github.com/HAPS-Collaboration
* HAPS-KaFF1.0: https://github.com/HAPS-Collaboration/HAPS-KaFF1.0
* arXiv: https://arxiv.org/abs/2606.16754
* INSPIRE: https://inspirehep.net/literature/3168717

