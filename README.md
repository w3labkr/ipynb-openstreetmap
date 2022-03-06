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

## Nominatim Service

Open Source search based on OpenStreetMap data

Nominatim (from the Latin, 'by name') is a tool to search OpenStreetMap data by name and address (geocoding) and to generate synthetic addresses of OSM points (reverse geocoding). An instance with up-to-date data can be found at https://nominatim.openstreetmap.org. Nominatim is also used as one of the sources for the Search box on the OpenStreetMap home page.

- <https://nominatim.openstreetmap.org/ui/search.html>
