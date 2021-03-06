**Howk's notes for learning Python**

This repository contains a few iPython notebooks to keep notes on some of the issues I've come across / solved in learning Python. Mostly meant for personal use, but feel free to go through / comment on them if you find them helpful.

This work uses `astropy, matplotlib, numpy`.

Most notebooks should work with either Python 2 or 3, though Python 3 is assumed.

**Current notebooks** /guides (if just starting, go in this order):

* **LearningPython.basics.ipynb:** How to treat arrays, make basic plots, and even just get the basic importing functionality right.

* **LearningPython.IO.ipynb:** Read and write basic ASCII, LaTeX, and FITS files.

* **LearningPython.SpectralPlots.ipynb:** Slightly more advanced plots, focused on making multiple plots in a stack. Useful for plotting spectral results (includes some GBT data as an example).

* **LearningPython.units-M31halo.ipynb** Calculating the mass of the CGM about M31 to demonstrate the use of units and constants in `astropy`.

* **LearningPython.FUSECatalogQuery.ipynb** Using Python to query the entirety of the FUSE exposure catalog.

* **LearningPython.astroquery.ipynb** Using the `astroquery` module to query Simbad.

**Advanced notes:**
* **Advanced.Axis Breaks.ipynb** Examples of plotting with "broken" axes, gaps in the x or y plot ranges.

* **Advanced.CalculateImpactParameters.ipynb** An example using `astropy.coordinates` and `astropy.cosmology` tools to calculate impact parameters for galaxies with respect to a QSO.

* **Advanced.MCMCfit.ipynb** An example of fitting a power law function to a dataset using the MCMC code `emcee`.

**Special:**
* **ccdproc-Example.ipynb** Examples on using the python implementaiton of CCDproc from the dev team.

* **COS-Halos.DatabaseAccess.ipynb** Notes on accessing information in the COS-Halos database of JXP's `pyigm`.

* **Hafen-voronoi_plotting.ipynb** Zach Hafen's notes on plotting using Voronoi binning.

* **Max's Brown Seeds.ipynb** Example plotting and simple statistics using a sample of the number of seeds in brown "mustache plant" seed pods (from Max Howk).
