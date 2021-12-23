Notebooks for generating NDWI median images for simplified Agro-Ecalogical Zones (AEZs) and pick stratified random samples.

Required:
1. Shapefiles for the simplified AEZs, excluding large permanent water bodies.
2. Shapefile defining 150 km x 150 km tiles that covers the continent.

The notebooks are:
1. NDWI_composite.ipynb: generate NDWI median images for all tiles inersecting a AEZ
2. Check_ndwi_composite.ipynb: check the output median images contain valid data
3. WOfS_summary_distribution.ipynb: calculate water detection frequency distributions for the AEZs. 
This will help select NDWI thresholds for stratified sampling.
4. Sampling.ipynb: merge NDWI composites, classify into selected number of classes and pick random samples from all classes.  
5. Label_fix_thresh.ipynb: classify NDWI median image using fixed thresholds.
6. Label_fix_thresh_large_area.ipynb: classify NDWI median image using fixed thresholds for a really big region.
7. Sampling_labeled.ipynb: random sampling from classified NDWI image.