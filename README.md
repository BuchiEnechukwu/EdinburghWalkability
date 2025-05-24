# Geospatial Analysis: the City of Edinburgh

An in-depth geospatial analysis assessing pedestrian accessibility in Edinburgh using OpenStreetMap data and R. This project aims to identify key barriers to walkability, unpack spatial patterns of infrastructure and safety concerns, and inform urban planning and public health strategies.



## Introduction

Built environment shape how people move, interact, and engage with their city. This analysis evaluates walkability by mapping pedestrian pathways, amenities, and safety attributes. By highlighting areas with infrastructure gaps or elevated safety concerns, we can guide targeted interventions to improve public health and urban resilience.



## Data Sources

- **OpenStreetMap (OSM)**  
  - Pedestrian pathways, footways, crossings, and points of interest  
  - Retrieved via the `osmdata` R package (data dump date: April 2024)  
- **Local Authority Boundaries**  
  - Provided by the City of Edinburgh Council (shapefiles)  
- **Supplementary Policy Documents**  
  - 15 urban planning and public health policy texts (for thematic context)
 

## Methodology
1.	Data Acquisition:
  - Retrieved OSM data for Edinburgh, focusing on pedestrian-related features such as footways, crossings, and amenities.
2.	Data Processing:
  - Utilized the osmdata package to extract relevant geospatial data.
  - Processed and cleaned the data using sf and tidyverse packages to prepare for analysis.
3.	Walkability Assessment:
  - Developed composite indicators to measure walkability, considering factors like sidewalk availability, intersection density, and proximity to amenities.
  - Employed network analysis using igraph to understand connectivity and accessibility.
  - Conducted routing analysis with osrm to estimate walking times to key destinations.
4.	Visualization:
  - Created interactive maps using leaflet to display walkability scores and highlight areas with varying levels of pedestrian accessibility.


## Results

- Identified neighborhoods with high walkability scores, characterized by dense networks of footpaths and close proximity to amenities.
- Highlighted areas lacking pedestrian infrastructure, suggesting opportunities for urban development and policy interventions.
- Demonstrated the effectiveness of combining OSM data with R for urban walkability studies.



## Conclusion & Recommendations

Edinburgh’s urban areas offer high walkability, but the less urban areas have less infrastructure deficits and safety issues. Recommendations include:

1. **Improve Lighting & Crossings** in low-scoring wards  
2. **Expand Pedestrian Pathways** along major thoroughfares  
3. **Targeted Community Engagement** to co-design local walking routes



## Future Work
-	Incorporate temporal data to assess changes in walkability over time.
-	Expand the analysis to include other cities for comparative studies.
-	Integrate additional data sources, such as traffic patterns and public transportation networks, to enrich the analysis.



## Installation & Usage

```bash
# Clone the repository
git clone https://github.com/BuchiEnechukwu/EdinburghWalkability.git
cd EdinburghWalkability

# Install required R packages
install.packages(c("osmdata", "sf", "tidyverse", "leaflet", "igraph", "osrm"))

# Run the main analysis script
Rscript scripts/run_walkability_analysis.R
```


## Author

Emeka Onyebuchi Enechukwu
GitHub: BuchiEnechukwu
