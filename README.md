
# README: Vegetation Canopy Height Analysis of Ravi-Chenab Interfluve Sub-Basin

## Project Overview
This project provides a high-resolution geospatial assessment and eco-hydrological analysis of vegetation canopy height across the Ravi-Chenab Interfluve Sub-Basin in Punjab, Pakistan. Leveraging 1-meter resolution Global Canopy Height Model (CHM) datasets from Meta and WRI, combined with WWF HydroSHEDS and Google Earth Engine (GEE) cloud computation, the project maps and classifies canopy structures, providing insights into forest architecture, anthropogenic modification, and eco-hydrological patterns.

**Author:** Mazhar Shakoor  
**Role:** Scholar & Geospatial Research Lead  
**Data Sources:** Meta / WRI Global CHM (1m), WWF HydroSHEDS  
**Analysis Platform:** Google Earth Engine API & JavaScript

## Repository Contents
- CSV Files: `ee-chart (1)(1).csv`, `ee-chart (2)(1).csv` - canopy height frequency statistics.
- Images/PNG: `infographic.png`, `Study Area map 3(1).jpg`, `a_high_detail_academic_infographic_poster_report.png`, `vegetation_canopy_height_analysis_report.png` - maps and infographic panels.
- TXT Reports: `Mapping and Analyzing Canopy Heigh(1).txt`, `Ravi Chenab  final Mapping and Analyzing Canopy Heigh(1).txt` - methodology and statistical analysis.
- Word Document: `Final_Canopy_Height_Analysis_Ravi_Chenab_Region.docx` - complete report.
- SVG: `ee-chart(1).svg` - vector histogram for interactive use.

## Study Area
Ravi-Chenab Interfluve Sub-Basin (HydroBASINS Level 6), spanning the corridor between Ravi and Chenab rivers, covering sub-montane margins near Sialkot/Jammu and Rechna Doab plains.

## Key Objectives
1. Spatial Delineation: Isolate HydroBASINS Level 6 boundary for sub-basin.
2. Vegetation Discrimination: Mask non-vegetated areas, urban/industrial zones, and water bodies.
3. Structural Classification: 
   - Class 1: 0–5 m (Low Canopy)
   - Class 2: 5–10 m (Medium Canopy)
   - Class 3: 10–20 m (High Canopy)
   - Class 4: >20 m (Dense Overstory)
4. Interactive Deployment: GEE scripts with legends, maps, and histograms.

## Methodology
- Data Sources: 1m CHM raster, HydroBASINS Level 6 vector boundaries.
- Processing: Mosaic CHM images, mask non-vegetated areas, classify canopy height.
- Visualization: Histograms, spatial maps, and classified canopy maps using GEE.
- Interactive Infographic: Panels with study area, histogram, canopy architecture, and ecological insights.

## Key Findings
- Weighted Mean Canopy Height: 3.10 m.
- Maximum Canopy Height: 29 m.
- Class Distribution:
  - Class 1 (0–5 m): 80.12%
  - Class 2 (5–10 m): 11.96%
  - Class 3 (10–20 m): 7.71%
  - Class 4 (>20 m): 0.21%
- Low canopy dominance indicates agricultural modification; sparse high-overstory areas require conservation.

## Interactive Infographic Features
- Pan and zoom on sub-basin map.
- Hoverable histogram for canopy pixel distribution.
- Toggle canopy height classes.
- Legends with color-coded height classes.

## Tools & Technologies
- Google Earth Engine (JavaScript API)
- Meta/WRI CHM 1m raster data
- WWF HydroSHEDS boundaries
- Python/CSV for histogram processing
- SVG and PNG for charts and infographic panels

## Citation
Shakoor, M. (2026). *Vegetation Canopy Height Analysis of the Ravi-Chenab Interfluve Sub-Basin.* University Thesis (In Progress).# Ravi-Chenab-Canopy-Analysis
High-resolution vegetation canopy height analysis of the Ravi-Chenab sub-basin using GEE and CHM datasets
<img width="1908" height="723" alt="Screenshot 2026-05-22 190135" src="https://github.com/user-attachments/assets/a3d30271-acd0-4e8f-9e33-227a39263991" />
<img width="1442" height="755" alt="Study Area map 3" src="https://github.com/user-attachments/assets/3afed507-f64d-4382-a076-7eed39bcdf43" />
<img width="1448" height="1086" alt="Infographic" src="https://github.com/user-attachments/assets/c84acc42-a494-4db4-92e7-44042eaa19e0" />
<img width="1496" height="629" alt="ee-chart (2)" src="https://github.com/user-attachments/assets/65375911-206d-430d-b579-af93ed47fb23" />
<img width="1496" height="629" alt="ee-chart (1)" src="https://github.com/user-attachments/assets/ee95a357-224b-4209-859d-b3bb7b36af01" />
