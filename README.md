# ifc-sample-files


- https://github.com/buildingsmart-community/Community-Sample-Test-Files
- https://openifcmodel.cs.auckland.ac.nz/
- https://github.com/bimdata/BIMData-Research-and-Development/blob/master/pages/IFC_FILES.md

### advanced_sample_project
From https://github.com/Xeraoo/ifc_hello_world/blob/master/IFC_files/rac_advanced_sample_project.ifc
* [rac_advanced_sample_project.ifc](https://github.com/Xeraoo/ifc_hello_world/blob/master/IFC_files/rac_advanced_sample_project.ifc)
* [rme_advanced_sample_project.ifc](https://github.com/Xeraoo/ifc_hello_world/blob/master/IFC_files/rme_advanced_sample_project.ifc)
* [rst_advanced_sample_project.ifc](https://github.com/Xeraoo/ifc_hello_world/blob/master/IFC_files/rst_advanced_sample_project.ifc)

### Snowdon Towers
https://github.com/digitalbuilderben/ai-bim-vibe/tree/main/models

### Golden Gate Bridge

Open the [IFC model](Golden_Gate_Bridge/Golden%20Gate%20Bridge.ifc) first, then the [2023 lidar survey](Golden_Gate_Bridge/Golden%20Gate%20Bridge%202023.laz) to compare them in the same scene. Both use NAVD88 elevations in metres.

- Flinker reconstructed the bridge exterior in IFC4x3 using survey measurements and the bridge district’s published dimensions. The model uses WGS 84 / UTM zone 10N (EPSG:32610). [Apache License 2.0](Golden_Gate_Bridge/LICENSE-IFC.txt) · [Golden Gate Bridge District dimensions](https://www.goldengate.org/bridge/history-research/statistics-data/design-construction-stats/)
- The LAZ contains all 21,854,294 survey returns in a 90 m wide corridor through the bridge and approaches. Flinker cropped the public-domain USGS 3DEP survey by USGS and NV5 Geospatial. The LAZ retains the point coordinates in WGS 84 / Pseudo-Mercator (EPSG:3857), NAVD88 heights, and laser intensity. [Survey record](https://www.fisheries.noaa.gov/inport/item/73386/full-list) · [USGS reuse terms](https://www.usgs.gov/3d-elevation-program/about-3dep-products-services)
