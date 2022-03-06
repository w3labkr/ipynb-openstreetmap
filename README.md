# GIS

Geographic Information System

## Environment

To create a virtualenv for the Python version used with pyenv

```shell
$ pyenv virtualenv 3.8.5 gis
```

Sets a local application-specific Python version

```shell
$ pyenv local gis
$ pyenv shell gis
```

## Dependencies

- tqdm
- numpy
- pandas
- geopandas
- geopy
- matplotlib
- networkx
- osmnx
- scikit-learn


## Packages

import packages

```shell
(gis) pip install -r requirements.txt
```

export packages

```shell
(gis) pip freeze > requirements.txt
```

## Reference

- **Openstreetmap**
The Rails application that powers OpenStreetMap
<https://www.openstreetmap.org>

- **Nominatim**
Open Source search based on OpenStreetMap data

- **Open Source Routing Machine**
Open Source Routing Machine - C++ backend
<https://github.com/Project-OSRM/osrm-backend>

- **Open Source Routing Machine Frontend**
Modular rewrite of the OSRM frontend using LRM
<https://map.project-osrm.org>

- **osmnx**
OSMnx: Python for street networks. Retrieve, model, analyze, and visualize street networks and other spatial data from OpenStreetMap.
<https://geoffboeing.com/publications/osmnx-complex-street-networks/>

- **networkx**
Network Analysis in Python
<https://networkx.org/>
