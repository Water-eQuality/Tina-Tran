# Tina-Tran
Individual repository for the Water (e)Quality Bren School Master's Group Project (2025-2026), in partnership with Heal the Bay.

## About This Repository

This repository contains all materials for the fecal indicator bacteria(FIB), precipitation, and WMMS 2.0 analysis components of the Water (e)Quality project. 

## Repository Structure

```
Tina Tran/
├── data/                                         # Data inputs FIB v precipitation analysis
│   ├── beach_data_dry period.csv                 # FIB beach data for dry period (May to October)
│   ├── beach_data_wet_period.csv                 # FIB beach data for wet period (November to April
│   ├── beach_site_summary_table.csv              # name of all FIB beach monitoring sites
│   ├──clean_master_beach_data_2014_2024.csv      # FIB beach monitoring data from 2014-2024
│   ├── exceed_v_prcp_stat_coef.csv               # Binomial logistic regression results FIB v Precipitation
│   ├── precipitation_clean_2014_2024.csv         # Precipitation data from 2014-2024
│   ├── wmms                                      # WMMS 2.0 model output data and analysis results & figures
        ├── analysis         # Data ouptut for potential reduction and loading of surface otuflow, nitrogen, sediment  
        ├── park_rec         # Model outputs for 10 selected park recommendations
        ├── school_rec       # Model outputs for 10 selected school recommendations
├── docs/                                         # Documentation and reference materials for WMMS 2.0
│   ├── 85th_Percentile_Storm.pdf
│   ├── Avg_and_90th_WaterYear.pdf
│   ├── Bacteria_Storm.pdf
│   ├── LSPCUtil_UserDocument (1).pdf
│   ├── LSPC_Version_5.0_User_Manual_DRAFT_12-6-17 (2).pdf
│   ├── OptimizationUtilitiesUserDocument (2).pdf
│   ├── Phase II Report_ BMP Model and Optimization Framework_July2020.pdf
│   ├── ULAR_Progress_Report_Stormwater_Projects_2024.pdf
│   ├── WRAMPSUtilityUserDocument.pdf                        
├── outputs/                                     # Generated figures and analysis outputs
│   ├── beach_fib_average_annually 
│   ├── beach_fib_average_monthly
│   ├── beach_timeseries_all 
│   ├── beach_timeseries_beachname
│   ├── beach_timeseries_entero_only                                
│   ├── beach_timeseries_entero_only_dash
│   ├── beach_timeseries_exceedances
│   ├── hydrographs
│   ├── precip_only
├── scripts/                                     # Analysis scripts
│   ├── beach_fib_average_annual.qmd             # Exploratory analysis of overall annual FIB trends
│   ├── beach_fib_timeseries.qmd                 # Timeseries analysis for FIB per monitoring station and per beach
│   ├── beach_fib_v_rain.qmd                     # Wet v Dry FIB concentrations and Hydrographs 
│   ├── wmms_clean_data.qmd                      # WMMMS 2.0 model output analysis for surface outflow, nitrogen, sediment
├── .gitignore
├── README.md
└── Tina-Tran.Rproj                      # RStudio project file
```

## Analysis Overview
The FIB and precipitation analysis address two main questions:
1. **Trends**: How does fecal indicator bacteria (FIB) change over the past ten years?
2. **Impact of Precipitation**: How does precipitation influence the concentrations of FIB on the beach level?

The WMMS 2.0 analysis address one main questions:
1. **Potential Reductions**: What are the potential reductions of FIB considering if a stormwater capture project was designed for an 85th percentile storm using surface outflow volume, nitrogen loading, and sediment loading as a proxy for the recommended sites?


## Data Sources

- **Beach FIB Data**: California State Water Resources Control Board beach monitoring data
- **Precipitation Data**: Heal the Bay's internal copy 
- **WMMS 2.0 Modeled Data**: Watershed Modeling Management System (WMMS) desktop model application outputs

## Contact

Tina Tran — ttran839@bren.ucsb.edu
Bren School of Environmental Science & Management, UC Santa Barbara
