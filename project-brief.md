# My project brief

## The question
Which parts of Chikwawa and Nsanje districts have the highest flood exposure, based on elevation and rainfall patterns over the past 10 years?

## Why it matters
Chikwawa and Nsanje sit in the Lower Shire Valley and are among the districts most frequently hit by flooding in Malawi, including major events in 2015 and 2019 that displaced tens of thousands of people and damaged crops, roads, and homes. Knowing which specific areas combine low elevation with high rainfall exposure can help direct early warning, planning, and disaster response resources to where they're needed most, rather than treating the whole valley as equally at risk.

## What I will do
1. Download and clip the rainfall, elevation, waterway, and population datasets to Chikwawa and Nsanje districts.
2. In QGIS, identify low-lying areas from the elevation data and overlay them with 10-year rainfall totals/patterns from CHIRPS.
3. Add roads, buildings, and waterways to see what infrastructure and settlements sit in the higher-exposure zones.
4. Overlay population data to see roughly how many people are in these zones.
5. Produce a map (and short write-up) showing relative flood exposure across the two districts.

## What I'm expected to find
Likely the highest exposure will cluster in low-lying land close to the Shire River and its tributaries, particularly in areas with a history of past flood events. I expect a fairly uneven pattern — some parts of each district look much higher-risk than others, rather than risk being spread evenly across the whole valley. This is a hypothesis to test, not a conclusion — the actual data may show something different.

## The data I need
- Rainfall — CHIRPS (Climate Hazards Center, UCSB) — https://data.chc.ucsb.edu/products/CHIRPS-2.0/ — GeoTIFF — ~1GB/year (daily, Africa clip)
- Elevation — Copernicus DEM GLO-30 via OpenTopography — https://opentopography.org — GeoTIFF — ~200–500MB (Malawi clip)
- Roads, buildings, waterways — OpenStreetMap Malawi via Geofabrik — https://download.geofabrik.de/africa/malawi-latest-free.shp.zip — Shapefile — ~20–50MB
- Population — WorldPop Malawi — https://hub.worldpop.org — GeoTIFF — ~50–100MB/year
- Admin boundaries — HDX Malawi COD-AB — https://data.humdata.org — Shapefile/GeoPackage — <10MB

