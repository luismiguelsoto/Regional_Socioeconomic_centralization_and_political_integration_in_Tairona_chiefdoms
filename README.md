Socioeconomic centralization and political integration in Tairona chiefdoms of the Río Frío basin, Sierra Nevada de Santa Marta, Colombia
--------------------------------------------------------------

This repository contains the R code and data used to analyze the processes of political integration and socioeconomic centralization in the Tairona chiefdom communities of the Río Frío basin (Sierra Nevada de Santa Marta, Colombia) of the Tairona period (from approximately the 10th to the 16th century A.D).

Repository Structure:
----------------------------------
1. Database:
   - Contains the Excel files with the datasets used in the analysis:
     • Buritaca_Desgrasantes.xlsx
     • Buritaca_Desgrasantes_attr.xlsx
     • Buritaca_Tipos.xlsx
     • Buritaca_Tipos_attr.xlsx
     • Neguanje_Desgrasantes.xlsx
     • Neguanje_Desgrasantes_attr.xlsx
     • Neguanje_Tipos.xlsx
     • Neguanje_Tipos_attr.xlsx
     • Tairona_Desgrasantes.xlsx
     • Tairona_Desgrasantes_attr.xlsx
     • Tairona_Tipos.xlsx
     • Tairona_Tipos_attr.xlsx

2. GIS:
   - Contains the spatial data files (shapefile components) defining the study area:
     • POLYGON_SURVEY_UNTILL_2023.shp
     • POLYGON_SURVEY_UNTILL_2023.dbf
     • POLYGON_SURVEY_UNTILL_2023.shx
     • POLYGON_SURVEY_UNTILL_2023.prj
     • POLYGON_SURVEY_UNTILL_2023.cpg

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
  • sf: e.g., version 1.0-0 (built under R 4.4.2; linking to GEOS 3.12.2, GDAL 3.9.3, PROJ 9.4.1) - installed 1.0.19 
  • spdep: (built under R 4.4.2) - installed 1.3.7 
  • ggplot2: e.g., version 3.3.6 - installed 3.5.1 
  • viridis: installed 0.6.5 
  • car: installed 3.1.3 
  • spatstat.explore: e.g., version 3.3-2 - installed 3.3.2 
  • spatstat.geom: e.g., version 3.3-3 - installed 3.3.3 
  • spatstat.model: e.g., version 3.3-2 - installed 3.3.2 
  • network: installed version 1.18.2 (update available: 1.19.0) - installed 1.18.2 
  • ggspatial: (built under R 4.4.2) - installed 1.1.9 
  • vegan: e.g., version 2.6-8 - installed 2.6.8 
  • scales: installed 1.3.0 
  • dplyr: installed 1.1.4 
  • patchwork: installed 1.3.0 
  • tidygraph: installed 1.3.1 
  • ggraph: installed 2.2.1 
  • GGally: installed 2.2.1 
  • FSA: e.g., version 0.9.5 - installed 0.9.5 
  • stats: - installed 4.4.1 
  • ggpubr: installed 0.6.0 
  • writexl: installed 1.5.1 
  • openxlsx: installed 4.2.7.1 
  • sna: e.g., version 2.8 (created on 2024-09-07) - installed 2.8 
  • statnet: e.g., version 2019.6 (2019-06-13) - installed 2019.6 
  • igraph: installed 2.0.3 
  • DT: installed 0.33 
  • tnet: installed 3.0.16 
  • kableExtra: installed 1.4.0 
  • readxl: installed 1.4.3 
  • dunn.test: installed 1.3.6 
  • ggdist: installed 3.3.2 

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
