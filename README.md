# cluster_islands_renewable_energy

Simple clustering of islands based on renewable energy availability. This is a simple educational project that should help you get started with the [Google Earth Engine](https://earthengine.google.com/) API. The main steps of this project are:
- Extract islands from the [LISB 2017](https://developers.google.com/earth-engine/datasets/catalog/USDOS_LSIB_SIMPLE_2017?hl=it) dataset and the [JRC Global Surface Water Mapping Layers](https://developers.google.com/earth-engine/datasets/catalog/JRC_GSW1_4_GlobalSurfaceWater?hl=it) dataset by selecting the landmasses that have a prevalence of water surrounding them;
- Associate to the extracted islands solar and wind power availability from the [ERA5-Land Monthly Aggregated](https://developers.google.com/earth-engine/datasets/catalog/ECMWF_ERA5_LAND_MONTHLY_AGGR) dataset.


## What's in here?
Here you can find two folders and a notebook:
- `figures` which contains the results of the extraction of the islands (given the hyperparameters in the associated notebook) and the results of the clustering (given the hyperparameters in the associated notebook).
- `data` which contains the extracted dataset of islands (with the renewable energy features, but without the clusters).
- `clustering_islands.ipynb` is the example notebook containing island extraction, feature definition, and clustering.



