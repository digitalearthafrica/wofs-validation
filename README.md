# wofs-validation
Code and data for validation of WOfS in Africa.

## Repository convention
 - `Results/Beta` contain results from the Landsat Collection 2 Provisional WOfS data
 - `Results/ls_wofs` contains results from operational (Collection 2 not-Provisional) WOfS data
 - "CEO" refers to Collect Earth Online, the spatial analysis tool used to consolidate validation data
 - `ndwi_sampling` folder contains all stratified sampling code (originally from the `sandbox-notebooks` repository)

## Quick reference
 - Stratified sampling strata were defined in `ndwi_sampling/04_Sampling`
 - The WOfS database is queried for the first 5 days before and after the start of each calendar month - see `Notebooks/02_Processing`
 - AEZ shapefiles are available from `Data/AEZs`