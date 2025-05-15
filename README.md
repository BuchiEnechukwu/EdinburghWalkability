# Walkability Analysis in Edinburgh Using OpenStreetMap and R
This project presents a geospatial analysis of walkability in Edinburgh, Scotland, utilizing OpenStreetMap (OSM) data and R programming. The study aims to assess pedestrian accessibility and infrastructure, providing insights into urban planning and public health implications.

## Project Overview
•	Objective: To evaluate the walkability of Edinburgh by analyzing pedestrian pathways, amenities, and infrastructure using OSM data.
•	Tools & Technologies:
•	Data Sources: OpenStreetMap
•	Programming Language: R
•	Key Libraries: osmdata, sf, tidyverse, leaflet, igraph, osrm
## Methodology
1.	Data Acquisition:
•	Retrieved OSM data for Edinburgh, focusing on pedestrian-related features such as footways, crossings, and amenities.
2.	Data Processing:
•	Utilized the osmdata package to extract relevant geospatial data.
•	Processed and cleaned the data using sf and tidyverse packages to prepare for analysis.
3.	Walkability Assessment:
•	Developed composite indicators to measure walkability, considering factors like sidewalk availability, intersection density, and proximity to amenities.
•	Employed network analysis using igraph to understand connectivity and accessibility.
•	Conducted routing analysis with osrm to estimate walking times to key destinations.
4.	Visualization:
•	Created interactive maps using leaflet to display walkability scores and highlight areas with varying levels of pedestrian accessibility.
## Key Findings
•	Identified neighborhoods with high walkability scores, characterized by dense networks of footpaths and close proximity to amenities.
•	Highlighted areas lacking pedestrian infrastructure, suggesting opportunities for urban development and policy interventions.
•	Demonstrated the effectiveness of combining OSM data with R for urban walkability studies.
## Future Work
•	Incorporate temporal data to assess changes in walkability over time.
•	Expand the analysis to include other cities for comparative studies.
•	Integrate additional data sources, such as traffic patterns and public transportation networks, to enrich the analysis.
## Author
Onyebuchi Enechukwu# EdinburghWalkability
