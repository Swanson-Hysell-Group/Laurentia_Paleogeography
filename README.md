# The Precambrian paleogeography of Laurentia

This repository contains a manuscript that is in preparation for a forthcoming book entitled *Ancient Supercontinents and the Paleogeography of the Earth*. This chapter focuses on the paleogeography of the Precambrian interior of North American known as Laurentia.

The contents of this repository are licensed for reuse under a [Creative Commons Attribution (CC BY 4.0)](http://creativecommons.org/licenses/by/4.0/) license.

## Manuscript

The .tex source file as well as the compiled manuscript are within this folder.

## Data

The pole compilations as well as the shapefiles associated Laurentia provinces and terranes are within this folder.

## Models

Published paleogeographic models as well as the minimal Laurentia model developed for this study are within this folder.

## Code

The code that conducts the analyses and develops the visualizations for the manuscript are within Jupyter notebooks within this folder. There are four notebooks:
- Laurentia_pole_compilation.ipynb *This notebook imports the paleomagnetic poles and calculations and analysis such as the implements the Euler rotations and calculations of paleolatitude. The summary figures of pole position and paleolatitude are developed in this notebook.*
- Laurentia_reconstructions_generate.ipynb *This notebook uses pygplates to generate reconstructions using the paleogeographic models and shapefiles. It also generates motion path calculations that are plotted along with the paleolatiudes of poles within Laurentia_pole_compilation.ipynb.*
- Laurentia_reconstructions_plot.ipynb *This notebook plots the reconstructed shapefiles that were generated in the Laurentia_reconstructions_generate.ipynb notebook.*
- Laurentia_tectonic_summary.ipynb *This notebook develops the tectonic summary figure for the manuscript*
The notebooks can be viewed statically at this link: https://nbviewer.jupyter.org/github/Swanson-Hysell-Group/Laurentia_Paleogeography/tree/master/Code/

The Python 3.7 environment for Laurentia_tectonic_summary.ipynb, Laurentia_pole_compilation.ipynb and 	Laurentia_reconstructions_plot.ipynb is specified within the laurentia_paleogeography.yml file. If one is using an Anaconda installation of Python, they can create this environment with the following command: 

```conda env create -f laurentia_paleogeography.yml```

Additionally, these notebooks utilize the PmagPy project (https://github.com/PmagPy) which can be installed using pip:

```pip install pmagpy```

The Laurentia_reconstructions_generate.ipynb notebook uses a Python 2.7 environment as that is required for the use of the pygplates package. That environment can be created using the pygplates.yml file.

```conda env create -f pygplates.yml```

Additionally, an installation of pygplates is required (www.gplates.org) to run the  Laurentia_reconstructions_generate.ipynb notebook.

## Reconstructions

Reconstructions that are output from the code are within this folder.
