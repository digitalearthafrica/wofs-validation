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
 - `02_Processing`
 - `03_Accuracy_Assessment-AEZ`
 - `03_Accuracy_Assessment-Continental`
 - `04_Accuracy_Assessment_Seasonal`
 - `04_Monthly_Accuracy` Accuracy calculated per AEZ per month. Accuracy is shown to be temporally affected likely due to weather conditions and lack of clear observations
 - `05_Monthly_climate_data` CHPclim climate data is used to calculate long-term average precipitation for each month per AEZ (i.e. January long term average, February long term average)