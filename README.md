Socioeconomic centralization and political integration in Tairona chiefdoms of the Río Frío basin, Sierra Nevada de Santa Marta, Colombia (Caution, data under preparation)
--------------------------------------------------------------

This repository contains the R code and data used to analyze the processes of political integration and socioeconomic centralization in the Tairona chiefdom communities of the Río Frío basin (Sierra Nevada de Santa Marta, Colombia) of the Tairona period (from approximately the 10th to the 16th century A.D).

Repository Structure:
----------------------------------
1. Database:
   - Contains the Excel files with the datasets used in the analysis:
     • TAIRONA_STRUCTURES_UNTIL_2025.xlsx
     • MULTIPLE_REGRESSION_MODEL_UNTIL_2025.xlsx

2. GIS:
   - Contains the spatial data files (shapefile  and raster components) defining the study area:
     • COMMUNITIES_TAIRONA_UNTIL_2025.shp
     • FUNCTIONAL_CERAMICS_TAIRONA_PERIOD_SITES_UNTIL_2025.shp
     • RIO_FRIO_POLYGON_SURVEY_UNTIL_2025.shp
     • STRUCTURES_DBSCAN_UNTIL_2025.shp
     • TAIRONA_SITES_UNTIL_2025.shp
     • DEM_POLYGON_SURVEY_UNTIL_2025.tiff    

3. R Code Files:
   - The main R script (or R Markdown file) contains the code to:
     a) Load required packages.
     b) Download the Excel datasets and GIS files directly from GitHub.
     c) Process the data, build similarity matrices, calculate centrality metrics, and perform network analysis.
     d) Generate the figures and tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.4.1]
- Key R packages used in this project include (with version numbers):
  • car: 3.1.3
  • cluster: 2.1.6
  • dbscan: 1.2.2
  • dendextend: 1.19.0
  • dplyr: 1.1.4
  • gplots: 3.2.0
  • ggplot2: 3.5.1
  • ggspatial: 1.1.9
  • lmtest: 0.9.40 
  • movecost: 2.1
  • patchwork: 1.3.0
  • scales: installed 1.3.0 
  • dplyr: installed 1.1.4 
  • patchwork: installed 1.3.0 
  • tidygraph: installed 1.3.1 
  • ggraph: installed 2.2.1 
  • GGally: installed 2.2.1 
  • psych: 2.5.6
  • proxy: 0.4.27
  • readxl: 1.4.3
  • raster: 3.6.32
  • sf: 1.0.19
  • smacpod: 2.6.4
  • sp: 2.1.4
  • spdep: 1.3.8
  • spatstat: 3.3.2
  • spatstat.explore: 3.4.2
  • spatstat.geom: 3.3.6 
  • stats: 4.4.1
  • scales: 1.3.0 
  • tmap: 4.0
  • writexl: 1.5.1  

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R script (or R Markdown file) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the Excel and GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the syntax or contact the corresponding author.

Manuscript Summary:
----------------------------------
This article explores the social and political organization of the Tairona period in the Río Frío basin of northern Colombia, proposing that settlements were structured around two supralocal centers accompanied by multiple local communities, all with varying degrees of social centralization and political integration. The absence of a central place suggests a low level of hierarchization, and independent forms of decisionmaking and of economic autonomy. It is concluded that the coexistence of multiple forms of social organization prevented the formation of highly centralized political entities as suggested by earlier scholars.

For questions or further information, please contact:
lms313@pitt.edu
