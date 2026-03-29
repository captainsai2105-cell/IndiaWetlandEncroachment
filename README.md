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
   All data used is free and publicly available.
   - Wetland polygons: github.com/yashveeeeeeer/india-geodata
   - Satellite imagery: Google Earth Engine (Sentinel-2, Copernicus)
   - District boundaries: india-geodata GitHub

   ## Tech Stack
   Python, Google Earth Engine, geemap, geopandas, QGIS

   ## Setup instructions
   *(Coming soon — will be updated as the tool is built)*

   ## Author
   Prateek Sai | Associate Ecologist | Gurugram, India