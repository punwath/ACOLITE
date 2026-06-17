This Jupyter notebook runs [ACOLITE](https://github.com/acolite/acolite) in bulk
over a folder of Landsat scenes stored as `.tar` bundles (Collection-2 Level-1
archives from USGS EarthExplorer). It loops through every scene in the input
directory and applies Dark Spectrum Fitting (DSF) atmospheric correction with a
tiled aerosol estimate, exporting atmospherically-corrected surface reflectance
(`rhos_*`) as NetCDF products to the output directory.
