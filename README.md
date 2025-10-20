# EDS-223 Exploring patterns of environmental justice Assignment 2

## Project Summary
This repository contains the code, data references, and outputs for Homework 2: an exploration of historical redlining in Los Angeles and its legacy for present-day environmental justice and biodiversity sampling (bird observation 2021-2023). The analysis uses vector and raster spatial operation in R, produces multi-layer maps with **tmap**, and generates summary visualization with **ggplot2**.

Learning outcomes:
- Build effective, responsible, accessible, and aesthetically-pleasing maps. 
- Manipluate vector and raster data and combine layers.
- Make maps in R using `tmap` and visualization with `ggplot2`.

## Repository structure

```
├───data
│   ├───ejscreen
│   │   └───EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
│   ├───gbif-birds-LA
│   └───mapping-inequality
└───__MACOSX
    └───data
        ├───ejscreen
        │   └───EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
        ├───gbif-birds-LA
        └───mapping-inequality
```
## Data 

1. EJScreen (2023) - Environmental justice screening data from the U.S. EPA

 - Contains census block group level environmental and demographic indicators
 - Technical documentation included in download
 - Column descriptions included in download

2. Mapping Inequality - Historical HOLC redlining maps from the Digital Scholarship Lab at University of Richmond

 - Digitized 1930s Home Owners' Loan Corporation neighborhood grades

3. GBIF Bird Observations - Bird sighting data from 2021-2023 in Los Angeles County

 - Sourced from the Global Biodiversity Information Facility

[Data can be accessed here](https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view)

### Author: 

**Ixel M.** 

[GitHUb](https://github.com/IIDonaji)

## Course Information

The analysis for this assignment was done for EDS 223: Geospatial Analysis and Remote Sensing at the Bren School of Environmental Science & Management, UC Santa Barbara.

**Instructor:** Annie Adams

**Language: R**

## References

**Data Citation:**

- Ellis-Soto, D., Chapman, M., & Locke, D. H. [2023](https://www.nature.com/articles/s41562-023-01688-5). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nature Human Behaviour, 1-9.

- gbif-birds-LA: GBIF.(n.d.) [https://www.gbif.org/](https://www.gbif.org/)

- United States Environmental Protection Agency. 2023. EJSCREEN 2023. Retrieved: October 6, 2025, [Here](www.epa.gov/ejscreen) 
  - [EPA EJScreen map](https://pedp-ejscreen.azurewebsites.net/)