# Figures and figure-producing files

This folder contains figures generated for the WOfS paper and general use. It contains Jupyter Notebooks, shapefiles, and SVGs required to reproduce and edit the figures.

*SVG files can be edited in Inkscape, a free vector graphic software.*

| **File**                            | **Produces the files**                 | **Comments**                                                                                                                                        |
|-------------------------------------|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| `Plot_WOfS_by_country.ipynb`        | `wofs_pc_change_*.png`                 | Default notebook settings use 1 km resampling with `nearest`. Upper/lower bounds, temporal extent are defined in the notebook / exported filenames. |
|                                     | `Plot_WOfS_by_country-data/wofs_pc_change_*.geojson` | Interim geodataframe data export - use to modify an existing plot.                                                           |
|                                     | `chirps_per_country_*.png`             | CHIRPS rainfall data averaged over the year for each country.
| `Plot_WOfS_by_country-data/african_countries.shp/dbf/prj/shx` | NA                                     | Shapefile used by `Plot_WOfS_by_country.ipynb`.                                                                           |
| `WOFL_to_Summary_text.svg`          | `WOFL_to_Summary_text.png`             | Walkthrough of WOfS WOFL to annual to all-time summary process. Brief text description included.                                                    |
| `WOFL_to_Summary_notext.svg`        | `Summary_infographic.png`              | Export a section of the image by selecting the desired layers then clicking File > Export PNG Image > Selection.                                    |
|                                     | `WOFL_infographic.png`                 |                                                                                                                                                     |