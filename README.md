# InSAR_forward_model_resolution
A tool to project forward models of displacement into InSAR line-of-sight at a resolution of your choice.

Inputs: 
* csv-format file of x and y locations of points of interest and modeled displacements at those points (in x, y and z); UTM coordinates highly recommended
* gdal-readable files of InSAR geometry (elevation and azimuth angles $-$ see https://hyp3-docs.asf.alaska.edu/guides/insar_product_guide/#optional-files)

Requirements:
* pygmt (includes numpy, pandas and gdal)
* jupyter
