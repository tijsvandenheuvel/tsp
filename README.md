# tsp

The goal of this project is to find the shortest route between all the 581 municipalities (gemeentes) in Belgium.

The graph and the route are calculated in the `TSP.ipynb` notebook, this takes in the `municipalities.geojson` file.

The `municipalities.geojson` dataset is created in the `TSPcreateDataset.ipynb` notebook, getting the geodata from the OSM Overpass API, storing it in `villages.geojson` and filtering it with the `municipalityNames.txt` and `municipalityNamesExtra.txt`.

## data source

municipality shapes come from [ArcGIS Hub](https://hub.arcgis.com/datasets/9589d9e5e5904f1ea8d245b54f51b4fd/explore?location=51.006906%2C4.621885%2C9.72)

