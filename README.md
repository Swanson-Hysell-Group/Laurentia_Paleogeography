# The Precambrian paleogeography of Laurentia

This repository contains a manuscript that is in preparation for a forthcoming book entitled *Ancient Supercontinents and the Paleogeography of the Earth*. This chapter focuses on the paleogeography of the Precambrian interior of North American known as Laurentia.

The contents of this repository are licensed for reuse under a [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](http://creativecommons.org/licenses/by-nc/4.0/) license.

## Code

The Python 3.7 environment for Laurentia_tectonic_summary.ipynb, Laurentia_pole_compilation.ipynb and 	Laurentia_reconstructions_plot.ipynb is specified within the laurentia_paleogeography.yml file. If one is using an Anaconda installation of Python, they can create this environment with the following command: 

```conda env create -f laurentia_paleogeography.yml```

Additionally, these notebooks utilize the PmagPy project which can be installed using pip:

```pip install pmagpy```

The Laurentia_reconstructions_generate.ipynb notebook uses a Python 2.7 environment as that is required for the use of the pygplates package. That environment can be created using the pygplates.yml file.

```conda env create -f pygplates.yml```

Additionally, an installation of pygplates is required.
