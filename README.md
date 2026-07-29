# Perturbation Spectrum of Michel Flow: Acoustic, Vortical, and Entropy Modes

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21676691.svg)](https://doi.org/10.5281/zenodo.21676691)

This repository contains the preprint, LaTeX source, bibliography, and figures
for:

> [Alexander V. Semyannikov](https://orcid.org/0009-0007-0926-8272),
> “Perturbation Spectrum of Michel Flow: Acoustic, Vortical, and Entropy
> Modes” (2026).

## Abstract

This work studies the spectrum of linear perturbations of relativistic spherical
accretion onto a Schwarzschild black hole (Michel flow), extending the Newtonian
spatial-stability analysis of Bondi accretion to full general relativity. Small
perturbations of a perfect fluid split into acoustic, vortical, and entropy
modes, treated together in the language of acoustic geometry. The acoustic sector
reduces to a one-dimensional Schrödinger-type equation with an explicit effective
potential; for a transonic Michel background the sonic point coincides with the
acoustic horizon, which replaces the Newtonian central endpoint and regularizes
the exterior spatial problem. Vortical and entropy perturbations are advected
invariants carried through the horizon; the entropy mode additionally sources
sound and vorticity through a relativistic baroclinic term. Numerical
integration of the scattering problem confirms flux conservation and the
absence of superradiance.

## Repository contents

- `article.pdf` — compiled preprint
- `article.tex` — LaTeX source
- `article.bib` — bibliography database
- `figs/` — figures used in the article
- `CITATION.cff` — machine-readable citation metadata
- `.zenodo.json` — Zenodo deposit metadata

## Building the article

A TeX distribution with `latexmk`, BibTeX, and the `elsarticle` document class
is required. Build the PDF from the repository root with:

```sh
latexmk -pdf article.tex
```

To remove generated auxiliary files:

```sh
latexmk -c
```

## Citation

Please use the metadata in `CITATION.cff` when citing this work. The DOI for all
versions is [10.5281/zenodo.21676691](https://doi.org/10.5281/zenodo.21676691).

## License

The article, its source, and the accompanying figures are licensed under the
Creative Commons Attribution 4.0 International License (CC BY 4.0). See
`LICENSE` for details.
