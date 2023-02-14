# Validation Notebooks

Numbering convention is as follows:
 - `01` validation data clean and pre-processing
 - `02` validation data processing
 - `03` Landsat WOfS - geographic accuracy assessments
 - `04` Landsat WOfS - temporal accuracy assessments
 - `05` Landsat WOfS - ancillary data processing and analysis
 - `06` Sentinel-2 WOfS notebooks
 - `07` superseded notebooks, kept for record
 
 ## Notebook summary

 - `01_Inspect_CEO`
 - `02a_Processing`
 - `02b_Convert_Institution_to_AEZ` Validation points were collected by different institutions; here they are compiled into AEZs and cleaned
 - `03_Accuracy_Assessment-AEZ` Accuracy assessments per AEZ
 - `03_Plot_accuracy_maps` Show producer's / user's / overall accuracy for each AEZ on a single plot
 - `04_Wet-dry_season_accuracy` Extract and plot seasonal accuracy
 - `05_Compare_provisional_vs_production` Compares provisional C2 WOfS to production (not-provisional) C2 WOfS and identifies validation points where they have been differently identified by the products
 - `05_Monthly_climate_data` CHPclim climate data is used to calculate long-term average precipitation for each month per AEZ (i.e. January long term average, February long term average)
 - `06_Processing_S2`
 - `06_s2_Monthly_Accuracy`
 - `06_s2_Monthly_valid_data`
 - `07_ObservationPlotting` Overview of validation analysis and observation plotting