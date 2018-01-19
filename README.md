# pyLVT

**pyLVT** is a set of Python bindings and wrapper scripts to the LVT (Land Surface Verification Toolkit). LVT is a Fortran90/C application for evaluating the outputs of land surface models. PyLVT is intended to provide a simpler interface for pre-processing data for LVT ingestion, running the LVT core to produce statistaical metrics, and also (eventually) a set of Python/Matplotlib visualisation scripts for producing publication-quality figures of the analyses.

## Plan

pyLVT is under construction. The aims are:

 - Pre-processor scripts (for converting netCDF format files into the right format/layout)
 - LVT wrappers to run LVT and generate the right config file
  - (maybe these will become proper Python-Fortran bindings if there is time)
 - Visualisation scripts to plot commonly used analyses.

DV Jan 2018


