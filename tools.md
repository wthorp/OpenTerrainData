# OpenTerrainData
[Home](./README.md) An attempt to catalog free and opensource terrain data sources and tools

# Open source software

[Cesium](https://github.com/AnalyticalGraphicsInc/cesium)
Uses quantized mesh for terrain

[Web WorldWind](https://worldwind.arc.nasa.gov/web/)
Uses bil16 [raster] and geoserver for terrain

[WorldWind Java](https://worldwind.arc.nasa.gov/java/)
Uses bil16 [raster] and geoserver for terrain

# Closed source software
(* indicates free-as-in-beer)

*[ArcGIS Earth](https://www.esri.com/en-us/arcgis/products/arcgis-earth)
Seems to use [ArcGIS Server ImageServer](https://elevation3d.arcgis.com/arcgis/rest/services/WorldElevation3D/Terrain3D/ImageServer) [raster]

[ArcGlobe](http://desktop.arcgis.com/en/arcmap/latest/extensions/3d-analyst/3d-analyst-and-arcglobe.htm)
Seems to use [ArcGIS Server GlobeServer](http://services.arcgisonline.com/arcgis/services/Elevation/USGS_Elevation_US/GlobeServer)

*[Google Earth Enterprise](https://github.com/google/earthenterprise/wiki/Google-Earth-Enterprise-Client-(EC))
Uses a custom tiled-TIN (quantized-mesh-like)

# Tools

https://github.com/geoadmin/3d-forge
(python) Read/Write quantized-mesh tiles

https://github.com/geo-data/cesium-terrain-builder
(C++) tools to create terrain tiles for use with the Cesium JavaScript library

https://github.com/geo-data/cesium-terrain-server
(Go) A basic server for serving up filesystem based tilesets representing Cesium.js terrain models

https://github.com/loicgasser/quantized-mesh-tile
(Python) Quantized-mesh-tile is a Python encoder/decoder and topology builder for terrain tiles.

https://github.com/heremaps/tin-terrain
(C++) GeoTIFF format into tiled optimized meshes (Triangulated Irregular Network) with different levels of details
 
https://github.com/heremaps/quantized-mesh-viewer
(JS) debug individual tiles using THREE.js renderer

https://github.com/google/earthenterprise
(C) uses a custom tiled-TIN (quantized-mesh-like) 

https://github.com/tkrajina/go-elevations
(Go) SRTM parser for golang

https://github.com/tkrajina/srtm.py
(Python) SRTM.py is a python parser for the Shuttle Radar Topography Mission elevation data

