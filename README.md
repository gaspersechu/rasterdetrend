# Raster Detrending using Python
A Python notebook with a workflow for detrending a raster.
It works by fitting a surface plane to the raster surface, the plane then rotates the raster surface via the centroid.
The residuals from the surface fit are then added to the rotated plane.

## Requirements
Requires a few libraries such as gdal, osr, numpy, scipy...