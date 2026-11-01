# Spacetime Geometry, Black Holes, and Wormhole Topology

### A LaTeX compendium of the "gravity equation" material from *Interstellar*

[English](README.md) | [简体中文](README.zh-CN.md)

This repository contains a bilingual, XeLaTeX-typeset transcription of the dense
formula panels associated with the "gravity equation" in Christopher Nolan's
*Interstellar* (2014). The material is organized by topic into three parts and is
provided in both English and Simplified Chinese editions.

> **Unofficial transcription.** This is a fan-made document for study and
> documentation. It is not affiliated with, authorized by, or endorsed by the
> filmmakers or rights holders. All rights to the original film material remain
> with their respective owners.

## Editions

| Edition | LaTeX source | Compiled PDF |
| --- | --- | --- |
| English | [`main-en.tex`](main-en.tex) | [`main-en.pdf`](main-en.pdf) |
| Simplified Chinese | [`main.tex`](main.tex) | [`main.pdf`](main.pdf) |

Both editions are six pages and use the same equation set.

## Contents

1. **Fundamental Spacetime Geometry and Metric Structure**
   - Rotating black holes, dynamical spherical symmetry, and brane-world metrics
   - Modified gravity, effective actions, and field equations
   - Dispersion relations and quantum-gravity corrections
2. **Black Hole Physics and Accretion Disk Dynamics**
   - Relativistic magnetohydrodynamics and accretion disk structure
   - Black-hole energy extraction, thermodynamics, and microstates
   - Spacetime focusing, semiclassical stability, and the Casimir effect
   - Brane worlds, Euclidean actions, and ER=EPR
   - Quantum-corrected black holes, the Page curve, and the Teukolsky equation
   - Orbital energy loss, black-hole spin, and force-free electrodynamics
3. **Wormhole Physics and Spacetime Topology**
   - Wormhole geometry and energy conditions
   - Holographic entanglement, the SYK model, and effective wormhole theory

## Build

### Requirements

- XeLaTeX from a current TeX Live installation (tested with TeX Live 2025)
- `ctex` for the Simplified Chinese edition
- Standard packages: `amsmath`, `amssymb`, `mathtools`, `geometry`, `xcolor`,
  `titlesec`, `fancyhdr`, and `hyperref`

### Commands

```powershell
# English edition
xelatex main-en.tex
xelatex main-en.tex

# Simplified Chinese edition
xelatex main.tex
xelatex main.tex
```

Run XeLaTeX twice so that the PDF bookmarks and cross-reference data settle.

## Source and attribution

According to the provenance supplied with the screenshots, the formulas are the
"gravity equation" material associated with *Interstellar* (2014), directed by
Christopher Nolan.

This repository is an independent transcription project. It does not reproduce
film footage, and it does not claim to be an official production document. The
original screenshots are not redistributed here; only the LaTeX transcription and
compiled PDFs are included. If you reuse or adapt the transcription, please retain
this attribution and respect the rights of the original creators.

## Notes on the transcription

- Equations, tensor indices, and symbols follow the source images.
- Mathematical fonts, line spacing, sectioning, and page layout have been
  standardized for readability.
- The original material has been reorganized thematically rather than reproduced
  screenshot by screenshot.
- Some expressions are transcribed exactly as they appear, even where notation is
  nonstandard or internally inconsistent. No claim of physical correctness or
  mathematical completeness is implied.
- This is a manual transcription and may contain errors; corrections are welcome.

## License

No license has been selected for this repository yet. Before distributing modified
versions or allowing broad reuse, add a `LICENSE` file appropriate for your
purposes (for example, CC BY 4.0 for the original LaTeX transcription) and update
this section. Any third-party material remains subject to its own rights.

## Contributing

Corrections to the transcription and improvements to the typesetting are welcome
via issues or pull requests. Please quote the relevant equation and, when possible,
the corresponding screenshot.
