# Exploring Patterns of Environmental Justice in Los Angeles County
## About
This repository contains a geospatial analysis examining the legacy of 1930s redlining practices on present-day environmental justice and biodiversity observations in Los Angeles County. The analysis explores how historical discriminatory housing policies from the Home Owners' Loan Corporation (HOLC) continue to influence current environmental conditions, socioeconomic patterns, and citizen science data collection.

### HW2: Exploring patterns of environmental justice:
- build effective, responsible, accessible and aesthetically-pleasing maps
- practice manipulating vector and raster data to build multi-layer maps
- practice making maps in R, specifically using tmap

## Repository Structure:
```
eds223-HW2/
├───.gitignore
├───data/
|   └───ejscreen/
|   └───gbif-birds-LA/
|   └───mapping-inequality/
├───.Rhistory
├───eds223-HW2.Rproj
├───HW2.qmd
├───LICENSE
└───README.md

```
**Note:** The `data/` folder is included in `.gitignore` and is not tracked by version control due to file size. See below for data access instructions.

## Data
### Access
1. Download the data folder from [this Google Drive link](https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view?usp=sharing)
2. Unzip the downloaded folder
3. Place the unzipped `data/` folder in the **root directory** of this repository
4. Verify the folder structure matches the Repository Structure shown above


### Data Sources:
1. **EJScreen (2023)** - Environmental justice screening data from the U.S. EPA
   - Contains census block group level environmental and demographic indicators
   - Technical documentation included in download
   - Column descriptions included in download

2. **Mapping Inequality** - Historical HOLC redlining maps from the Digital Scholarship Lab at University of Richmond
   - Digitized 1930s Home Owners' Loan Corporation neighborhood grades

3. **GBIF Bird Observations** - Bird sighting data from 2021-2023 in Los Angeles County
   - Sourced from the Global Biodiversity Information Facility

## Author
**Emily Miller**
[Github](https://github.com/rellimylime)

## Course Information
This analysis was completed for EDS 223: Geospatial Analysis and Remote Sensing at the Bren School of Environmental Science & Management, UC Santa Barbara.

- **Instructor:** Annie Adams
- **Assignment:** [Homework 2 - Mapping Inequality](https://eds-223-geospatial.github.io/assignments/HW2.html)

## References
- Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. *Nature Human Behaviour*, 1-9.

- United States Environmental Protection Agency. 2023. EJSCREEN 2023. Retrieved: October 6, 2025, from www.epa.gov/ejscreen
> [EPA EJScreen Site](https://19january2021snapshot.epa.gov/ejscreen_.html)