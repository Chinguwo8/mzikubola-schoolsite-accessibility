# mzikubola-schoolsite-accessibility
Python-based GIS suitability mapping to identify potential locations for new primary schools in TA Mzikubola, Mzimba district, Malawi.
# Project Overview
This project applies Python and Geographic Information Systems (GIS) techniques to identify potentially suitable locations for constructing new primary schools in TA Mzikubola, Mzimba District, Malawi.
# Objectives
- Identify areas located within 500 metres of main roads.
- Exclude areas within 2 kilometres of existing primary schools.
- Exclude protected areas.
- Restrict the analysis to the study area's Traditional Authority boundary.
- Calculate the total suitable area in hectares and square kilometres.
- Produce a static map and an interactive web map of the suitable areas.
# Suitability Criteria
- Road accessibility: Within 500 m of main roads
- Existing primary schools: At least 2 km from existing primary schools
- Protected areas: Outside protected areas
- Study area: Within the TA boundary
# Tools and Technologies
- Python
- GeoPandas
- Pandas
- Folium
- Jupyter Notebook
- Matplotlib
# Methodology
The spatial datasets were processed using Python and GeoPandas. Road buffers were used to identify areas close to main roads, while buffers around existing primary schools were used to identify areas that did not meet the required separation distance. Protected areas were excluded, and the remaining suitable areas were restricted to the study area's boundary. The resulting suitable areas were measured, and maps were prepared to communicate the findings. Folium was used to create an interactive web map.
# Project Structure
1. mzikubola-schoolsite-accessibility/
- notebooks/
- data/
- outputs/
- README.md
# Outputs
- Jupyter Notebook documenting the analysis
- Static suitability map in PNG and PDF format
- Interactive HTML suitability map
# Limitations
The identified areas are preliminary candidates based on the specified spatial criteria. They should not be treated as confirmed construction sites without field verification and further assessment of population distribution, land ownership, terrain, land availability and other planning requirements.
# Reproducibility
To reproduce the analysis, download or clone the repository, install the required Python packages, ensure that the input datasets are available at the paths specified in the notebook, and execute the notebook cells in order.
# Data Sources
The analysis uses the Traditional Authority boundary, main roads, existing primary schools and protected areas datasets. These data were taken from the existing geological survey department datasets.
