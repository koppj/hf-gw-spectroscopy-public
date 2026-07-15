# High-Frequency Gravitational Wave Limits from Precision Spectroscopy

Dmitry Budker, Valerie Domcke, Joachim Kopp, Oleg Tretiak

arXiv:[2607.12617](https://arxiv.org/abs/2607.12617)

## Overview

This repository contains the code and data accompanying the paper. The Jupyter notebook `hf-gw.ipynb` computes the sensitivity of precision laser spectroscopy experiments to high-frequency gravitational waves, and produces the data for the red curves in fig. 2 of the paper.

The sensitivity plot itself was produced using a modified version of [HFGWPlotter](https://github.com/ctamaritd/HFGWPlotter_Sh), developed by Francesco Muia, Andreas Ringwald, and Carlos Tamarit.

## Contents

| Path | Description |
|------|-------------|
| `hf-gw.ipynb` | Main notebook (Python/Jupyter): computes strain sensitivity curves in fig. 2 from frequency-shift data |
| `hf-gw.nb` | Mathematica notebook: analytic derivation of the formulas in the paper |
| `data/2201.02042-fig-1-Cs-2019.csv` | δf/f sensitivity data for the Cs-2019 experiment (digitised from fig. 1 of [arXiv:2201.02042](https://arxiv.org/abs/2201.02042)) |
| `data/2201.02042-fig-1-Exp-A.csv` | δf/f sensitivity data for Experiment A (ibid.) |
| `data/2201.02042-fig-1-Exp-B.csv` | δf/f sensitivity data for Experiment B (ibid.) |
| `data/external-limits.json` | Strain sensitivity curves for external experiments (Holometer, LIGO-HF, MAGO, magnetic Weber bar) |

## Requirements

Python 3 with the following packages: `numpy`, `scipy`, `matplotlib`, `labellines`.

## License

Copyright (C) 2026 Dmitry Budker, Valerie Domcke, Joachim Kopp, Oleg Tretiak

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

See <https://www.gnu.org/licenses/> for details.
