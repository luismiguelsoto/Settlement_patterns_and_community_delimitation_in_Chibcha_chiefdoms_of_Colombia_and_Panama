Settlement patterns and community delimitation in Chibcha chiefdoms of Colombia and Panama (under review)
--------------------------------------------------------------

This repository contains code and data for a multi-method, multi-scale protocol for delimiting communities in archaeological settlement patterns. It integrates (1) IDW for density surfaces, (2) HDBSCAN on time-cost distances (topographic friction), and (3) k-NN networks with Leiden community detection. The protocol is applied comparatively to four pre-Hispanic sequences (Colombia and Panama): Río Frío, Fúquene, Parita, and Río Tonosí.

Repository Structure:
----------------------------------
1. GIS:
   - Contains the spatial data files (shapefile components and raster files) defining the study area:
     • POLYGON_RIO_FRIO_UTM_Polygons.shp
     • SITES_RIO_FRIO_TAIRONA_PERIOD_UTM_polygons.shp
     • POLYGON_FUQUENE_UTM_polygons.shp
     • SITES_FUQUENE_LATE_MUISCA_UTM_polygons.shp
     • POLYGON_PARITA_UTM_polygons.shp
     • SITES_PARITA_LATE_HATILLO_UTM_polygons.shp
     • POLYGON_TONOSI_UTM_polygons.shp
     • SITES_TONOSI_LATE_BIJAGUALES_UTM_polygons.shp

2. R Code Files:
   - The main R script (or R Markdown file) contains the code to:
     a) Load required packages.
     b) Download the Excel datasets and GIS files directly from GitHub.
     c) Process the data and perform network analysis.
     d) Generate the figures or tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.5.1]
- Key R packages used in this project include (with version numbers):
    •  boot: version 1.3-31
    •  car: version 3.1-3
    •  dbscan: version 1.2.3
    •  dplyr: version 1.1.4
    •  elevatr: version 0.99.1
    •  gdistance: version 1.6.5
    •  ggplot2: version 4.0.0
    •  ggrepel: version 0.9.6
    •  ggspatial: version 1.1.10
    •  gstat: version 2.1-4
    •  igraph: version 2.1.4
    •  kableExtra: version 1.4.0
    •  knitr: version 1.50
    •  mclust: version 6.1.1
    •  patchwork: version 1.3.2
    •  purrr: version 1.1.0
    •  raster: version 3.6-32
    •  scales: version 1.4.0
    •  scico: version 1.5.0
    •  sf: version 1.0-21
    •  sp: version 2.2-0
    •  spatstat.explore: version 3.5-3
    •  spatstat.geom: version 3.6-0
    •  spdep: version 1.4-1
    •  stats: version 4.5.1
    •  terra: version 1.8-60
    •  tidyr: version 1.3.1
    •  vegan: version 2.7-1
    •  viridis: version 0.6.5

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R script (or R Markdown file) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the Excel and GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the code or contact the corresponding author.

Manuscript Summary:
----------------------------------
Archaeological research on chiefdoms in the Intermediate Area has faced a methodological challenge to compare communities on an interregional scale due to the high variability in settlement patterns. This paper addresses this comparability problem by proposing a multi-method analytical protocol that integrates scales of social interaction based on landscape frictional travel cost. I apply this protocol to four pre-Columbian occupational sequences in Colombia and Panama (Río Frío, Fúquene lagoon, Parita valley and Río Tonosí) combining density interpolation (IDW), density-based clustering (HDBSCAN) and network analysis (k-NN/Leiden). From a methodological perspective, it is suggested that community is a scalar phenomenon; different methods capture distinct and interchangeable scales of social aggregation. Comparatively, it is suggested that, although high network segmentation (modularity) was a structural feature common to all four sequences, organizational strategies varied fundamentally. The main axes of variation were spatial hierarchy, site size, and degree of spatial agglomeration (clustered, random, or dispersed), which proved to be independent variables. The protocol successfully distinguishes between interaction networks and compact communities without strong sociopolitical hierarchy (Río Frío), dispersed but clustered with weak hierarchy (Fúquene), random with spatial hierarchy (Parita) and dense but spatially dispersed (Tonosí).

For questions or further information, please contact: lms313@pitt.edu
