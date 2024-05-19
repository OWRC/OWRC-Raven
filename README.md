# OWRC-Raven (v.2405)
A regional semi-distributed rainfall-runoff model built for the ORMGP jurisdiction.


[![](https://raven.uwaterloo.ca/images/RavenBannerWide.png)](https://raven.uwaterloo.ca/)

A regional semi-distributed rainfall-runoff model has been developed to simulate regional-scale hydrologic processes at the sub-watershed scale. The model is developed using Raven: a state-of-the-art [hydrological framework](https://raven.uwaterloo.ca/) written by Dr. James Craig at the University of Waterloo. In particular, the HBV-EC formulation is applied as its results can be mapped to the 60x60 grid used with the integrated [Water Budget model](/interpolants/modelling/waterbudgetmodel.html).

The model was initially built to support the Water Budget (recharge) model in that it is built on the same [sub-watershed network](/interpolants/interpolation/subwatershed.html), [land-use](/interpolants/interpolation/landuse.html), [surficial geology](/interpolants/interpolation/surfgeo.html) and [climate forcings](/interpolants/sources/climate-data-service.html). These files will update periodically as calibration is improved.