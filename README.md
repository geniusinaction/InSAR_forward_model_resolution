# InSAR_forward_model_resolution
A Jupyter notebook-based tool to project forward models of displacement into InSAR line-of-sight at a resolution of your choice.

Inputs: 
* csv-format file of x and y locations of points of interest and modeled displacements at those points (in x, y and z); UTM coordinates highly recommended
* gdal-readable files defining InSAR viewing geometry (elevation and azimuth angles $-$ see https://hyp3-docs.asf.alaska.edu/guides/insar_product_guide/#optional-files)

Example files are included so that you can try it out.

Requirements:
* pygmt (includes numpy, pandas and gdal)
* jupyter

You should be able to build a conda environment to run this with minimal difficulty:

conda create --name pygmt --channel conda-forge pygmt jupyter

(or use 'mamba' instead of 'conda' if you have it installed $-$ it's way faster)
