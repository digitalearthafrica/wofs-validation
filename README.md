# wofs-validation
Code and data for validation of WOfS in Africa. 
 - 01 ) Stratified sampling for validation
 - 02 ) Validation data pre-processing, analysis, and plots
 - 03 ) Figures for paper and further data visualisations
 
The actual validation data was collected externally using the Collect Earth Online tool. This chronologically happened between 01) and 02), during 2020 and 2021.

## 01_ndwi_sampling
Stratified sampling of WOfS, used for the product validation process.

*This data was originally generated from Landsat Collection 2 Provisional data.*

Re-running any of these notebooks will require a code update to use the latest Landsat products and DE Africa Tools package.
 - `shapes` folder: AEZ shapefiles and Landsat 8 tiles
 - `wofs_summary_aez` folder: summary of results for each AEZ
See folder README for notebook details.
 
## 02_Validation_data
Raw and pre-processed data collected from the validation analysts.
 
 - `CEO_raw_data` folder: Validation data exported from Collect Earth Online. Split by Implementing Partner organisation. Previously named `CEO`.
 - `Processed` folder: Results of `02_Validation_notebooks/01_Inspect_CEO` pre-processing notebook 
 - `AEZ_shapefiles` folder: AEZ shapefiles used in the validation notebooks
 
## 02_Validation_notebooks
Series of notebooks conducting the pre-processing, analysis, and plotting of WOfS data.

- `Plots` folder: Seasonal accuracy plots per AEZ; AEZ overall/producer's/user's accuracy maps per AEZ for provisional (beta) Collection 2 WOfS and non-provisional (production) Collection 2 WOfS; accuracy difference plot between the two

See folder README for notebook details.
 
## 03_Figures_for_paper
Figures, and code/files to produce figures for academic or general use. Folder README contains a description of parent and output files. Inkscape (open source software) can be used to edit the SVG files.


## Repository convention
 - `02_Validation_results/Beta` contain results from the Landsat Collection 2 Provisional WOfS data
 - `02_Validation_results/wofs_ls` contains results from operational (Collection 2 not-Provisional) WOfS data
 - "CEO" refers to Collect Earth Online, the spatial analysis tool used to consolidate validation data
 - `01_ndwi_sampling` folder contains all stratified sampling code (originally from the `sandbox-notebooks` repository)

## Quick reference
 - Stratified sampling strata were defined in `ndwi_sampling/04_Sampling`
 - The WOfS database is queried for the first 5 days before and after the start of each calendar month - see `Notebooks/02_Processing`
 - AEZ shapefiles are available from `02_Validation_data/AEZs`