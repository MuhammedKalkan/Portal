# Terrain Generator And Server (TGS)
TGS is a software that produces terrain data to be served primarily for [CesiumJS](cesiumjs.org) library.

Blog about the project [HERE](http://blog.terrainserver.com/).

You can preview live demo [HERE](http://www.terrainserver.com/) 

Try dataset on newest Cesium Version [HERE](http://cesiumjs.org/Cesium/Apps/Sandcastle/index.html?src=Hello%20World.html&label=Showcases&gist=35700c25799f93225d0c521a20272d7e)

Comments and inputs are quite welcome. You can follow progress from issues and here

## Latest News (16.04.2017)

Server migration and database generation / migration on progress. So live tilesets might be offline or some details missing time to time.

Water mask initial implementation results released. See blog for more details. 

## Published Tile Sets
### GTOPO 30
Initial dataset is derived from GTOPO30 sources. It has 1km resolution approx. for the whole world and i believe this tileset is identical with the Cesium one. They have added more data onto it so might be slight differences.

This dataset is detailed up to LEVEL 9  and consists of nearly 700K tile files. I have added this whole tileset available for download.

You can download [GTOPO30 Quantized Mesh Tileset](https://dl.dropboxusercontent.com/s/mplbvp84qtw6kko/Gtopo30QuantizedMesh.zip)


## Features
![Quantized Mesh Rendered Papua](https://dl.dropboxusercontent.com/s/f9dvgh7nwjpms60/6.png?dl=0)

CTGAS is usable at the moment as it is and have following features

1. **Heightmap** format terrain tile generation
2. **Quantized Mesh** format terrain tile generation
3. **KML** format terrain tile generation
4. Mesh Simplification Algorithm for tile generation
5. Multicore tile generation support
6. Tile Server in order to serve produced tiles

