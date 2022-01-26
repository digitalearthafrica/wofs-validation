# Figures and figure-producing files

This folder contains figures generated for the WOfS paper and general use. It contains Jupyter Notebooks, shapefiles, and SVGs required to reproduce and edit the figures.

*SVG files can be edited in Inkscape, a free vector graphic software.*

| **File**                            | **Produces the files**                 | **Comments**     |
|-------------------------------------|----------------------------------------|------------------|
| `Plot_WOfS_by_country.ipynb`        | `wofs_pc_change_*.png`                 | Default notebook settings use 30m default WOfS resolution which requires large sandbox. Upper/lower bounds, temporal extent, resolution are defined in the notebook / exported filenames. |
|                                     | `Plot_WOfS_by_country-data/wofs_pc_change_*.geojson` | Interim geodataframe data export - use to modify an existing plot.                                                           |
|                                     | `chirps_per_country_*.png`             | CHIRPS rainfall data summed over the year and subtracted.
| `Plot_WOfS_by_country-data/african_countries.shp/dbf/prj/shx` | NA                                     | Shapefile used by `Plot_WOfS_by_country.ipynb`.                                                                           |
| `WOFL_to_Summary_text.svg`          | `WOFL_to_Summary_text.png`             | Walkthrough of WOfS WOFL to annual to all-time summary process. Brief text description included.                                                    |
| `WOFL_to_Summary_notext.svg`        | `Summary_infographic.png`              | Export a section of the image by selecting the desired layers then clicking File > Export PNG Image > Selection.                                    |
|                                     | `WOFL_infographic.png`                 |                                                                                                                                                     |

# Figure gallery

|   2020 vs all-time, 1km res, water detected 0-75%   |  2020 vs all-time, 1km res, water detected 10-50%   |  2020 vs all-time, 1km res, water detected 20-75%   | 2020 vs all-time, 1km res, water detected 60-100%  |
|------------|-------------------|------------------|--------------------|
| ![](./wofs_pc_change_2020_vs_alltime_0-75.png)     | ![](./wofs_pc_change_2020_vs_alltime_10-50.png)     | ![](./wofs_pc_change_2020_vs_alltime_20-75.png)   | ![](./wofs_pc_change_2020_vs_alltime_60-100.png) |
|   2020 vs all-time, 1km res, water detected 75-100%   |  2020 vs all-time, 1km res, water detected 80-100%   |  2020 vs all-time, 30m res, water detected 1-100%   | 2020 vs all-time, 30m res, water detected 20-75%  |
| ![](./wofs_pc_change_2020_vs_alltime_75-100.png)     | ![](./wofs_pc_change_2020_vs_alltime_80-100.png)     | ![](./wofs_pc_change_2020_vs_alltime_1-100_30m-res.png)   | ![](./wofs_pc_change_2020_vs_alltime_20-75_30m-res.png) |
|   2019 vs all-time, 1km res, water detected 20-75%   |  2019 vs all-time, 30m res, water detected 20-75%   |   |  |
| ![](./wofs_pc_change_2019_vs_alltime_20-75.png)     | ![](./wofs_pc_change_2019_vs_alltime_20-75_30m-res.png)     |   |  |
|   2015 vs all-time, 30m res, water detected 20-75%   |   |   |  |
| ![](./wofs_pc_change_2015_vs_alltime_20-75_30m-res.png)     |   |   |  |
|   2014 vs all-time, 1km res, water detected 20-60%   |  2014 vs all-time, 1km res, water detected 20-75%   |  2014 vs all-time, 1km res, water detected 75-100%   | 2014 vs 2020, 1km res, water detected 20-60%  |
| ![](./wofs_pc_change_2014_vs_alltime_20-60.png)     | ![](./wofs_pc_change_2014_vs_alltime_20-75.png)     | ![](./wofs_pc_change_2014_vs_alltime_75-100.png)   | ![](./wofs_pc_change_2014_vs_2020.png) |
|   2014 CHIRPS vs CHPclim rainfall anomaly, 5km res   |  2015 CHIRPS vs CHPclim rainfall anomaly, 5km res   |  2019 CHIRPS vs CHPclim rainfall anomaly, 5km res   | 2020 CHIRPS vs CHPclim rainfall anomaly, 5km res  |
| ![](./rainfall_anomaly_per_country_2014_5km.png)     | ![](./rainfall_anomaly_per_country_2015_5km.png)     | ![](./rainfall_anomaly_per_country_2019_5km.png)   | ![](./rainfall_anomaly_per_country_2020_5km.png) |
|   WOFL infographic   |  WOFL to Summary with text  |  Summary infographic   |  |
| ![](./WOFL_infographic.png)     | ![](./WOFL_to_Summary_text.png)     | ![](./Summary_infographic.png)   | |