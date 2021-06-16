# Generating an Empirical Spatial Variogram

This repo is meant to address this [issue](https://github.com/nisar-solid/ATBD/issues/2#issue-892550063).Specifically,

> ### Statistical functions for comparison
> * Deramp --> [Raider deramp](https://github.com/dbekaert/RAiDER/blob/452cc9c429a0d34831640c6926a99e456ea051dd/tools/RAiDER/statsPlot.py#L345-L348)
> * Calculate experimental variogram --> [RAiDER variogram](https://github.com/dbekaert/RAiDER/blob/452cc9c429a0d34831640c6926a99e456ea051dd/tools/RAiDER/statsPlot.py#L327-L331)
> * Calculate binned variogram with functional fitting --> [RAiDER binning](https://github.com/dbekaert/RAiDER/blob/452cc9c429a0d34831640c6926a99e456ea051dd/tools/RAiDER/statsPlot.py#L358-L386) and [RAiDER fitting](https://github.com/dbekaert/RAiDER/blob/452cc9c429a0d34831640c6926a99e456ea051dd/tools/RAiDER/statsPlot.py#L388-L450)
> * Calculate double-difference --> [RAiDER pairs](https://github.com/dbekaert/RAiDER/blob/452cc9c429a0d34831640c6926a99e456ea051dd/tools/RAiDER/statsPlot.py#L288-L308)

Using the code above and this nice [reference](https://spatial.uchicago.edu/sites/spatial.uchicago.edu/files/5_variogram_r.pdf) regarding about variogram analysis and geospatial statistics, we put together some basic empirical varigoram analysis using outputs from [RAiDER](https://github.com/dbekaert/RAiDER) Data. The data is the mean/std of residual zenith delays when comparing RAiDER delays with GNSS.

## Installation

`pip install -r requirements.txt`