# Cesium Terrain Generator And Server (CTGAS)
CTGAS is a software that produces terrain data to be served primarily for [CesiumJS](cesiumjs.org) library.

CTGAS is written in Javascript just like Cesium itself. Cross platform and easy to install and use. 
As much as it is usable, there are lots of things to do so the source will be pending until it is ready to be released.

You can preview live demo [HERE](http://51.254.219.77/) 

You can get the source DEM data used for the showcase [HERE](http://naturalearth.springercarto.com/ne3_data/dem_large.zip)

Comments and inputs are quite welcome. You can follow progress from issues and here

## New Version Alpha

I have declared before that algorithm would change in future and i have been working on that for some time now. Development is still ongoing but i have decided to put it up online for a showcase demo. Since almost the entire software changed, there are features that need reimplementing such as multicore and data merge. After mesh generation is good enough to use these two will take turns. There are some flaws in generated terrain for now but hopefully it will come around.

Data source is same as before and can be downloaded from the link.
TIF support is removed since i actually dont see any use for it.

Here are a few scenes that shows tile details. You can browse live demo from the link up.

![Quantized Mesh Rendered Papua](https://dl.dropboxusercontent.com/s/f9dvgh7nwjpms60/6.png?dl=0)

## Features

CTGAS is usable at the moment as it is and have following features

1. **Heightmap** format terrain tile generation
2. **Quantized Mesh** format terrain tile generation
3. **KML** format terrain tile generation
4. Mesh Simplification Algorithm for tile generation
5. Multicore tile generation support
6. Tile Server in order to serve produced tiles

## IN PROGRESS
 Cesium terrain server like mesh generation
## TODO
1. Extensions coding
2. Interface to manage application
3. Code refactoring


## FUTURE WORK
1. Standalone server implementation

 Java and C++ porting of the software can be easily done. 
 
 ## Old Version Showcases (No Longer Available)

![Quantized Mesh Rendered North America](https://dl.dropboxusercontent.com/s/qtuosbpvoxysghj/1.png?dl=0)
![Quantized Mesh Wireframe](https://dl.dropboxusercontent.com/s/i9i7996xu5fg28s/2.png?dl=0)
![Quantized Mesh Rendered South America](https://dl.dropboxusercontent.com/s/q8sy0retoobducb/3.png?dl=0)
