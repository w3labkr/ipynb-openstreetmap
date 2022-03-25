# Openstreetmap

Various examples using OpenStreetMap

## Environment

To create a virtualenv for the Python version used with pyenv

```shell
$ pyenv virtualenv 3.8.5 openstreetmap
```

Sets a local application-specific Python version

```shell
$ pyenv local openstreetmap
$ pyenv shell openstreetmap
```

## Dependencies

- numpy
- pandas
- geopandas
- geopy
- matplotlib
- folium
- networkx
- osmnx
- scikit-learn
- igraph
- descartes
- wheel
- gdal
- rasterio

## Packages

import packages

```shell
(openstreetmap) pip install -r requirements.txt
```

export packages

```shell
(openstreetmap) pip freeze > requirements.txt
```

## Reference

- **Openstreetmap**  
The Rails application that powers OpenStreetMap  
<https://www.openstreetmap.org>

- **Nominatim**  
Open Source search based on OpenStreetMap data  
<https://nominatim.openstreetmap.org/ui/search.html>

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

- **osmnx-examples**  
Usage examples, demos, and tutorials for OSMnx.  
<https://github.com/gboeing/osmnx-examples>

## License

This software is licensed under the [MIT LICENSE](LICENSE).
