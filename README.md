# IndiaWetlandEncroachment

   A Python + Google Earth Engine tool that detects and visualises wetland area loss
   in Indian districts using publicly available satellite imagery and ISRO wetland data.

   ## Status
   🚧 In active development — Pilot district: Prayagraj, Uttar Pradesh

   ## What this tool does
   - Loads baseline wetland polygons from public ISRO/india-geodata sources
   - Pulls Sentinel-2 imagery for 2016 and 2024
   - Calculates NDWI (Normalised Difference Water Index) per wetland polygon
   - Detects area change and flags wetlands with >20% loss as "at risk"
   - Outputs a change map and CSV report

   ## Data Sources
| Dataset | Source | Format | Use |
|---|---|---|---|
| Water body polygons (UP) | India WRIS — DWA Phase 2 | Shapefile | Baseline water body boundaries |
| District boundaries | India WRIS — District_NWIC | Shapefile | Area of interest definition |
| Sentinel-2 imagery | Google Earth Engine | Raster | NDWI change detection |
| ISRO NWIA Atlas | vedas.sac.gov.in | PDF | Reference and validation |
   ## Tech Stack
   Python, Google Earth Engine, geemap, geopandas, QGIS

   ## Setup instructions
   *(Coming soon — will be updated as the tool is built)*

   ## Author
   Prateek Sai | Associate Ecologist | Gurugram, India


## Progress Log - 29/03/2026

   ### Phase 1 — Foundation & Setup ✅
   - Repository created and structured
   - Python environment configured with all required libraries
   - GEE Contributor account authenticated
   - Raw data downloaded and inspected in QGIS
   - Pilot district: Prayagraj, Uttar Pradesh
   - Water body data source: Water body polygons (UP) | India WRIS — DWA Phase 2