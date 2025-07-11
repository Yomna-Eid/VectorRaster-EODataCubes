# Raster-Vector Data Cubes for Earth Observation
### On 01.05.2025 @ [European Geosciences Union (EGU) 2025: SPM101](https://meetingorganizer.copernicus.org/EGU25/session/55010)
### On 23.06.2025 @ [ESA Living Planet Symposium (LPS) 2025: D.03.30 DEMO](https://lps25.esa.int/programme/programme-session/?id=F8A45A91-6492-462A-8FAB-C97EF4E61E4A)
&nbsp;

#### Description:

Geospatial datasets can be represented as either raster or vector data cubes, depending on the workflow requirements. Raster cubes store multi-dimensional arrays with coordinates like longitude and latitude, capturing the spatial aspects of a dataset. On the other hand, vector data, represented as geometry objects such as points, lines, and polygons, is traditionally stored as tables. Vector data cubes generalize this concept by having multi-dimensional arrays that include a geometry dimension to represent the spatial domain. 

In this tutorial, attendees will learn how to work with raster data cubes that cover large spatial extents to derive vector data cubes that focus on specific areas of interest, allowing us to observe how geospatial features and their attributes change over time. The participants will go through workflows for sampling and aggregating raster data cubes using vector geometries to produce vector data cubes, and explore different functions to show the advantages this provides over using raster data cubes, leveraging the languages R, Python, and Julia.

The presented case study was developed in the EU Horizon Europe Project ScaleAgData (101086355). We demonstrate how to create raster data cubes from Sentinel-2 derived Leaf Area Index (LAI) and Sentinel-1 catalogues that cover large spatial extents. We focus on demonstrating how to handle such datasets, which can be computationally challenging, by subsetting them to vector data cubes, limiting the analysis to the target areas within our farm boundary polygons and visualizing our results. Furthermore, we use the vector data cube for computing different statistical metrics, and we present how they can be used for machine learning modelling.
