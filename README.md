# Cbiomes2019Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gaelforget/Cbiomes2019Notebooks/master)

The included notebooks illustrate:

- 1) how ocean colour data and model ouptut can be used jointly in [CBIOMES](https://cbiomes.org) using the [Julia](https://julialang.org) language
- 2) how [Simons' CMAP](https://cmap.readthedocs.io/en/latest/) can be queried from within `julia` or `python` via [pycmap](https://github.com/simonscmap/pycmap)

<img src="https://raw.githubusercontent.com/gaelforget/Cbiomes2019Notebooks/master/figs/cbiomes-01.png" alt="Drawing" style="height: 100px;"/>

## `Notebooks/`

- `OceanColourAlgorithms.ipynb` provides simple recipes to compare model output and ocean color data.
- `ModelReflectanceMap.ipynb` uses `Plots.jl` to map output of the Darwin model and OC-CCI data.
- `DarwinCmapJulia.ipynb` uses [Simons' CMAP](https://cmap.readthedocs.io/en/latest/) to download output of the `Darwin` model as a file or dataframe using `julia`'s `pycall` package to call the `pycmap` python package.
- `DarwinCmapPython.ipynb` uses [Simons' CMAP](https://cmap.readthedocs.io/en/latest/) to map output of the Darwin model using the `pycmap` python package (this is a **python rather than julia** notebook).

## `src/`

Julia utility scripts.

