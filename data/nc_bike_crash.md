---
layout: data_dictionary
title: nc_bike_crash.csv
---

### Get the data

Two options listed below:

1. Click <a href="nc_bike_crash.csv" download="nc_bike_crash.csv">
*here*
</a> to download the dataset.


2. Alternatively, use the following lines of code to load the data in R using the following:

<div class="highlight">
    <code>
    bike <- read.csv("https://stat.duke.edu/~mc301/data/nc_bike_crash.csv",
    stringsAsFactors = FALSE)    
    </code>
</div>

### Data description

From [https://opendurham.nc.gov/](https://opendurham.nc.gov/explore/dataset/north_carolina_bicycle_crash_data_heatmap_/?tab=metas).

### Codebook

This data frame contains 5,716 observations (rows), each representing a bike crash, and 54 variables (columns):

1. `FID`
2. `OBJECTID`
3. `AmbulanceR`
4. `BikeAge_Gr`
5. `Bike_Age`
6. `Bike_Alc_D`
7. `Bike_Dir`
8. `Bike_Injur`
9. `Bike_Pos`
10. `Bike_Race`
11. `Bike_Sex`
12. `City`
13. `County`
14. `CrashAlcoh`
15. `CrashDay`
16. `Crash_Date`
17. `Crash_Grp`
18. `Crash_Hour`
1. `Crash_Loc`
1. `Crash_Mont`
1. `Crash_Time`
1. `Crash_Type`
1. `Crash_Ty_1`
1. `Crash_Year`
1. `Crsh_Sevri`
1. `Developmen`
1. `DrvrAge_Gr`
1. `Drvr_Age`
1. `Drvr_Alc_D`
1. `Drvr_EstSp`
1. `Drvr_Injur`
1. `Drvr_Race`
1. `Drvr_Sex`
1. `Drvr_VehTy`
1. `ExcsSpdInd`
1. `Hit_Run`
1. `Light_Cond`
1. `Locality`
1. `Num_Lanes`
1. `Num_Units`
1. `Rd_Charact`
1. `Rd_Class`
1. `Rd_Conditi`
1. `Rd_Config `
1. `Rd_Defects`
1. `Rd_Feature`
1. `Rd_Surface`
1. `Region`
1. `Rural_Urba`
1. `Speed_Limi`
1. `Traff_Cntr`
1. `Weather`
1. `Workzone_I`
1. `Location`