# CRU TS4.08

## Overview
The **Climatic Research Unit (CRU) Time-Series (TS) version 4.08 (CRU TS4.08)** dataset provides month-by-month variations in climate over the period **1901-2023**. It is produced by the **Climatic Research Unit (CRU) at the University of East Anglia**, funded by the **UK National Centre for Atmospheric Science (NCAS)**.

This dataset consists of high-resolution (0.5° x 0.5°) gridded climate data, based on observations from National Meteorological Services and other external sources.

## Data Variables
The CRU TS4.08 dataset includes the following climate variables:

- **Cloud cover (cld)**
- **Diurnal temperature range (dtr)**
- **Frost day frequency (frs)**
- **Potential evapotranspiration (pet)**
- **Precipitation (pre)**
- **Monthly average daily minimum temperature (tmn)**
- **Daily mean temperature (tmp)**
- **Monthly average daily maximum temperature (tmx)**
- **Vapour pressure (vap)**
- **Wet day frequency (wet)**

## Data Format
The dataset is available in both **ASCII** and **NetCDF** formats. The NetCDF versions include an additional integer variable (`stn`), which provides a count (between **0 and 8**) of the number of stations used in the interpolation for each datum. The missing value code for `stn` is **-999**.

**Important Note:** All CRU TS output files contain actual values **NOT anomalies**.

## Interpolation Method
CRU TS4.08 data were produced using **angular-distance weighting (ADW) interpolation**. Previous versions (prior to 4.00) used **triangulation routines in IDL**.

## Citation
> **University of East Anglia Climatic Research Unit; Harris, I.C.; Jones, P.D.; Osborn, T. (2024):** CRU TS4.08: Climatic Research Unit (CRU) Time-Series (TS) version 4.08 of high-resolution gridded data of month-by-month variation in climate (Jan. 1901 - Dec. 2023). **NERC EDS Centre for Environmental Data Analysis**. [DOI Link](https://catalogue.ceda.ac.uk/uuid/715abce1604a42f396f81db83aeb2a4b/)

## Download Instructions
To download the dataset, right-click on a filename and select **"Save As..."** or **"Save Link As..."**.

### Available Files:
```
cld/  # Cloud cover
dtr/  # Diurnal temperature range
frs/  # Frost day frequency
pet/  # Potential evapotranspiration
pre/  # Precipitation
tmn/  # Monthly average daily minimum temperature
tmp/  # Daily mean temperature
tmx/  # Monthly average daily maximum temperature
vap/  # Vapour pressure
wet/  # Wet day frequency
```

## License
Please refer to the official dataset page for licensing details.

## References
- [CRU TS4.08 Dataset Page](https://catalogue.ceda.ac.uk/uuid/715abce1604a42f396f81db83aeb2a4b/)
- [University of East Anglia - Climatic Research Unit](https://www.uea.ac.uk/groups-and-centres/climatic-research-unit)
