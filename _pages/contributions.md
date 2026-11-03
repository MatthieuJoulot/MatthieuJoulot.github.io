---
layout: single
title: "Open-Source"
permalink: /contributions/
author_profile: true
---

## Clinica

[Clinica](https://www.clinica.run/) ([GitHub](https://github.com/aramis-lab/clinica)) is an open-source software platform for clinical neuroimaging research developed at the Aramis Lab. I am an active contributor, with involvement spanning from June 2021 to the present.

**Key contributions:**
- Development of BIDS converters for neuroimaging datasets (ADNI, GENFI, OASIS-3)
- Refactoring of image processing pipelines from Nipype to Pydra
- Development of new processing pipelines (DWI preprocessing, spatial SVM)
- Software maintenance, bug fixes, and user support

---

## Community Engagement

[Nipype](https://nipype.readthedocs.io/) / [Pydra](https://github.com/nipype/pydra)
As an early adopter of both tools in the context of Clinica's migration to Pydra, I provided extensive user feedback that contributed to improving both tools and helped drive their adoption within the neuroimaging community.

[Nipoppy](https://nipoppy.readthedocs.io/)
I contributed to the conceptual development of the Nipoppy platform, specifically on questions related to the integration of longitudinal processing workflows.

---

## Brainhack

I have participated in the [OHBM Brainhack](https://brainhack.org/) in 2022, 2023, and 2026. During the 2022 edition I contributed to [Nilearn](https://nilearn.github.io/), a Python library for machine learning in neuroimaging. My participation in the 2023 edition is documented in the published proceedings ([DOI: 10.52294/001c.145051](https://doi.org/10.52294/001c.145051)). At the 2026 edition, I worked on integrating [Clinica](https://www.clinica.run/) pipelines into [Nipoppy](https://nipoppy.readthedocs.io/), with a specific focus on FreeSurfer longitudinal and SAMSEG longitudinal.

---

## Repositories

### [SAMSEG longitudinal for Nipoppy](https://github.com/MatthieuJoulot/nipoppy_samseg_long)

Nipoppy processing pipelines for SAMSEG longitudinal segmentation of brain MRI. The pipelines wrap FreeSurfer's `mri_robust_template` (which builds an unbiased within-subject template from a participant's T1w images across sessions) and `run_samseg_long` (longitudinal SAMSEG segmentation on template-space images). A citable record is available on [Zenodo](https://zenodo.org/records/21469881).

---

## Side projects

### [Open Sports Analysis](https://github.com/MatthieuJoulot/open_sports_analysis)

A local web application for analyzing sports activities recorded with
Garmin devices (cycling, running, hiking) from a local GarminDB SQLite
database. It detects, names and groups climbs, computes per-sport
statistics and best efforts, and offers GPS heatmaps, 3D flyovers and
training tracking. Python backend and JavaScript frontend, MIT licensed.

### [Open Ascent List](https://github.com/MatthieuJoulot/open-ascent-list)

An open database of road-cycling ascents: for each summit or pass, the
roads that climb to it, from the foot to the top. Distributed as GeoJSON
under the ODbL licence and open to contributions. It powers the climb
list of [Open Sports Analysis](https://github.com/MatthieuJoulot/open_sports_analysis).

### [GPX Library Viewer](https://github.com/MatthieuJoulot/gpx-library-viewer)

A minimal browser application for browsing a library of GPX files on a map. Tracks are grouped by collection, with filters and details such as distance, elevation gain and duration. MIT licensed.
