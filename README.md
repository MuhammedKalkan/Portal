# Terrain Generator And Server (TGS)
TGS is a software that produces terrain data to be served primarily for [CesiumJS](cesiumjs.org) library.

Twitter page [HERE](https://twitter.com/TerrainServer)

Blog about the project [HERE](http://blog.terrainserver.com/).

You can preview live demo [HERE](https://www.terrainserver.com/) 

Try dataset on newest Cesium Version with comparison to Cesium Terrain Server data [HERE](https://cesiumjs.org/Cesium/Apps/Sandcastle/?src=Hello%20World.html&label=Showcases&gist=662d86203a93fab5f8385c0360d4d70b)

Comments and inputs are quite welcome. You can follow progress from issues and here

## Features
* Cesium STK Terrain Server dataset file format read support
* Cesium STK Terrain Server dataset file format write support
* Quantized Mesh format tile generation
* KML format tile generation
* Tile Lighting Support
* Watermask Support
* High Throughout Tile Server

## Latest News (16.09.2017)

File Format Support Added

## Published Tile Sets
Note that these tilesets are for testing purposes. An Alpha version.

### PAMAP 1m
1 meters resolution for US, Carbon County, PA area only is now live on server. 

### NED 10m
10 meters resolution for US, Monument Valley area only is now live on server. 

### New Zealand
8 meters resolution for whole New Zealand is now live on server

### Norway
10 meters resolution for whole Norway is now live on server

### SRTM 30
This dataset includes 30 meters resolution between 60 / -60 latitudes. It is now live on server.

### GTOPO
Initial dataset is derived from GTOPO30 sources. It has 1km resolution approx. for the whole world and i believe this tileset is identical with the Cesium one. They have added more data onto it so might be slight differences.

This dataset is detailed up to LEVEL 9  and consists of nearly 700K tile files. I have added this whole tileset available for download.

You can download [GTOPO30 Quantized Mesh Tileset](https://dl.dropboxusercontent.com/s/mplbvp84qtw6kko/Gtopo30QuantizedMesh.zip)


## Features
![Quantized Mesh Rendered Papua](https://dl.dropboxusercontent.com/s/f9dvgh7nwjpms60/6.png?dl=0)
