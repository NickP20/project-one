# Project-One

https://github.com/shindokl90-lab/Project-One


Data source
-Catalog:  Data.gov
-Monthly provisional counts of deaths by age group and HHS region for select causes of death 
  https://catalog.data.gov/dataset/monthly-provisional-counts-of-deaths-by-age-group-and-hhs-region-for-select-causes-of-deat 
  Preview of data:  https://data.cdc.gov/NCHS/AH-Monthly-Provisional-Counts-of-Deaths-by-Age-Gro/ezfr-g6hf
     
Regions 1 - 10 (US is a row for total)


Parameters
Type of death / trends vs. years ( months) / regions


Questions
1. We are looking at how cause of death by diseases counts changed from 2019 (March - Feb 2020) vs. 2020 (March - Feb 2021) with the onset of Covid
    -Is age a factor in cause of death (age distribution for different causes of death)

    -Does seasonality or location impact death by certain causes

4. How did the onset of Covid 19 impact the distribution of cause of death (2019 vs. 2020)

5. Covid only vs. covid with underlying conditions (2020 data only)

6. Age distribution for Covid 


NOTES:

-HHS Region is for US (United States total) or (1-10) regional  
-Surpressed seems to appear in the "flag" columns (not sure what they are for), don't see in other columns
--But, there are both NuN and "0" values in the other (non Flag) rows

-Notes column - indicates when data is provisional and values in the most recent months are incomplete

-allcause vs. natural cause - went to the CDC website and they talk about natural causes vs. external causes (accidents) so assuming that allcause = all deaths, and naturalcause = disease 
-- also, it doesn't seem that the sum of the listed diseases ='s naturalcause

-Covid multiple causes vs underlying - best I can tell it is contributing vs. primary
--Covid death's don't start appearing until early 2020, so looks clean 


SORTS:

-Region, age, year/month, cause of death 


NEXT STEPS:

-


VISUALIZATIONS:

-NOTE: can layer without merging from different data source
