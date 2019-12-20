# `nomisma-geopandas`


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/neelsmith/nomisma-geopandas/master)



## What's here

Notebooks with a few simple examples of cartographic plotting of point data (here, read from a `csv` file with locatoins of mints extracted from `nomisma.org` data sets) along with modern national boundaries (using data from [Natural Earth](https://www.naturalearthdata.com/)).  I'm trying to get familiar enough with python's numerous excellent map plotting libraries to provide cartographic views of data from `nomisma.org` in Juptyter notebooks.


## Running these notebooks

Notebooks in this repository can be used on [`mybinder.org`](https://mybinder.org/v2/gh/neelsmith/nomisma-geopandas/master).


The `mybinder` configuration files are based on `https://github.com/jorisvandenbossche/geopandas-tutorial`.  Notebooks from that repository:  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jorisvandenbossche/geopandas-tutorial/master)


Another way to use at least some of these notebooks locally is to run this docker container:

    docker run -it --rm -p 8888:8888 -v shared:/home/jovyan/work brunorpinho/geoscience-notebook:latest
