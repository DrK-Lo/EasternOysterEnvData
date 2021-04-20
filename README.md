
# Information about the data

- [old repo, previous analysis done by Erin](https://github.com/MarineEvoEcoLab/OysterGenomeProject/tree/master/popstructureOutliers/data/environment)
- some issues with data used; some issues with not filtering out bad data

- [Google drive for final environmental data by thais](https://drive.google.com/drive/folders/1gsdFaAyLbL1BcN6Ss4fb1TjRDr-K7vaL?usp=sharing)

- Filtered, clean environment data [Site_Envi_Data_QC202011_Thais](https://drive.google.com/drive/folders/1gsdFaAyLbL1BcN6Ss4fb1TjRDr-K7vaL)

- [List of populations and data source for each population](https://docs.google.com/spreadsheets/d/1UPv-Lo2Ak2PhheqoyhA-HvnRhvn80Mdw85bakwYTvFU/edit?pli=1#gid=488191574) 
  - Entered by Thais in Dec 2020 
  - Skip the selection line populations - populations whose name ends in an "S"

- [List of datasources and what filters were applied, data cleaning](https://docs.google.com/spreadsheets/d/1ySYfxii6Z8q7BmNCyhmOYNfLbcpDIpsFER24YW5m08M/edit#gid=1467712745)

- [Map of all Wild Populations and their respective environmental data locations](https://www.google.com/maps/d/edit?mid=1-ViurISNSSC9OIeHt1w02nIc-fzWxsrE&usp=sharing) FIX THIS LINK

- [Map of bouy sites that have salinity data]() NEED TO UPDATE LINK


# What we want to calculate for each dataset

### Apply filters

NERR data: 

### Temperature
* Mean_Annual_Temperature_C	: average of all available data
* Mean_max_temperature_C	: average of (maximums for each year)
* Mean_min_temperature_C	: average of (minimums for each year)
* Temperature_st_dev: SD of all available data (if only daily averages are reported separately from mean/max daily this SD could be biased)
* Temperature_n: number of datapoints
* Temperature_years: number of years
*	dd_0: number of days where temp fell below 0
* dd_15: number of days where temp above 15C
* dd_30: number of days where temp above 30C

### Salinity
* Mean_Annual_Salinity_ppt	: average of all available data
* Salinity_st_dev	: SD of all available data (if only daily averages are reported separately from mean/max daily this SD could be biased)
* Mean_min_Salinity_ppt	: average of (minimums for each year)
* Mean_max_Salinity_ppt : average of (maximums for each year)
* Salinity_n: number of datapoints
* Salinity_years: number of years

## The following populations from the resequencing project do not have salinity data:

- NJ_DB_CS_Med_W
- ME_SR_SM_Low_W
- NY_LI_LH_High_W
- NY_LI_CM_High_W
