# GOST PublicGoods
This repository contains the various libraries, tools, scripts, notebooks and other documentation used by the Geospatial Operations Support Team

# Libraries:
## GOSTNets
GOSTnets is a python library that pulls together a series of functions for rapid, scale independent analysis of physical connectivity between locations using open source data. 

  Installation instructions
  
    Download from GitHub the latest copy of GOSTnets. Unzip the folder into your location of choice, [location]​

    Make a new Python 3.6 environment in Anaconda Navigator. Call it [env name]​

    Install the following packages in this order:​

    conda install –c conda-forge geopandas ​

    pip install osmnx​

    pip install peartree​

    conda install rasterio​

    pip install ipykernel​

  Register your sparkly new environment with Jupyter:​

    source activate myenv ​

    python -m ipykernel install --user --name [env name] --display-name "Python ([env name])" ​


## GOSTrocks
 
GOSTrocks is a python library that pulls together routine raster processing functions for transforming spatial data into tables useful to economists

