---
permalink: /software/
title: "Software"
gallery:
  - url: software/MARRMoT_sample.png
    image_path: software/MARRMoT_sample.png
    alt: "Example MARRMoT results, comparison of three models"
    title: "Example MARRMoT results, comparison of three models"
---

## MARRMoT
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2482541.svg)](https://doi.org/10.5281/zenodo.2482541)
[![GitHub release](https://img.shields.io/github/v/release/wknoben/MARRMoT?include_prereleases)](https://github.com/wknoben/MARRMoT/)

{% include gallery %}

I contributed to developing the Modular Assessment of Rainfall-Runoff Models Toolbox (MARRMoT) v2.x. MARRMoT is a flexible modelling framework written in MATLAB reproducing the behaviour of 47 established hydrological models. It can be used to calibrate and run models in a user-friendly and consistent way and is designed to facilitate the sharing of model code for reproducibility and to support intercomparison between hydrological models. Additionally, it allows users to create or modify models using components of existing ones.
Check out the articles describing MARRMOT on Geoscientific Model Development to learn more:
1. [Knoben et al. (2019)](https://doi.org/10.5194/gmd-12-2463-2019) for the motivation and original development of the framework;
2. [Trotter et al. (2022)](https://doi.org/10.5194/gmd-15-6359-2022) for the structural improvements from v1 to v2.

**To install and use MARRMoT:**
- `EITHER:` Download a copy of the files from [the repository](https://github.com/wknoben/MARRMoT/) and extract the files in an appropriate directory;
- `OR:` (Optionally fork and) clone [the repository](https://github.com/wknoben/MARRMoT/) onto your own machine.

Then
- Open Matlab;
- Add the `MARRMoT` folder  and its subfolders `Functions`, `Models` and `User Manual` to the Matlab path;
- Check out the sample workflows in the `User Manual` folder or read the [User Manual](https://github.com/wknoben/MARRMoT/blob/master/MARRMoT/User%20manual/v2.-%20User%20manual.pdf) to get started

## Other resources
I have also developed a MARRMoT friendly implementation of the Dynamic Identifiability Analysis algorithm (or DYNIA from [Wagener et al., 2003]( https://doi.org/10.1002/hyp.1135)). It is available from my [GitHub page](https://github.com/ltrotter/DYNIA_MARRMoT).
