# vernon-etal_2023_scidata

**Harmonized geospatial data to support infrastructure siting feasibility studies for regional scale energy system transitions**

Chris R. Vernon<sup>1\*</sup>, Kendall Mongird<sup>1</sup>, Jennie S. Rice<sup>1</sup>, and Kristian Nelson<sup>1</sup>

<sup>1 </sup> Pacific Northwest National Laboratory, Richland, WA. 99354

## Abstract
Climate change, energy system transitions, and socioeconomic change are compounding influences affecting the growth of electricity demand. While energy efficiency initiatives and distributed resources can address a significant amount of this demand, the United States will likely still need new utility-scale generation resources. The energy sector uses capacity expansion planning models to determine the aggregate need for new generation, but these models are typically at the state or regional scale and are not equipped to address the wide range of location- and technology-specific issues that are increasingly a factor in power plant siting. To help address these challenges, we have developed the Geospatial Raster Input Data for Capacity Expansion Regional Feasibility (GRIDCERF) data package, a high-resolution product to evaluate siting suitability for renewable and non-renewable power plants in the conterminous United States. GRIDCERF offers 265 suitability layers for use with 56 power plant technology configurations in a harmonized format that can be easily ingested by geospatially-enabled modeling software. It also provides pre-compiled technology-specific suitability layers and allows for user customization to robustly address science objectives when evaluating varying future conditions.

## Journal reference
Vernon, C.R., Mongird, K., Rice, J.S., and Nelson, K. Harmonized geospatial data to support infrastructure siting feasibility studies for regional scale energy system transitions. _Sci Data_, in review.

Jupyter Notebooks to support GRIDCERF development and validation

## Project Data
Vernon, C. R., Mongird, K., Nelson, K., & Rice, J. S. (2023). GRIDCERF: Geospatial Raster Input Data for Capacity Expansion Regional Feasibility (v1.1.3) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.8218921

## Reproduce my work
All code used to create and validate data used in this publication can be reproduced using the following Jupyter notebooks.  

These notebooks require Python 3.8 and up.  You can install the requirements in a virtual environment using the `requirements.txt` file provided in this repository.


| **Notebook**                              | **Description**                                                                      |
|-------------------------------------------|--------------------------------------------------------------------------------------|
| build_airport_suitability.ipynb           | Generates proximity to airport suitability layers                                    |
| build_bia_land_area_representations.ipynb | Generates Bureau of Indian Affairs (BIA) land area representation suitability layers |
| build_coalmines_railnodes_navwaters_suitability.ipynb | Generates proximity to coal supply suitability layers | 
| build_common_suitability.ipynb | Builds all common suitability layers | 
| build_compiled_suitability.ipynb | Compiles all technology suitability layer |
| build_earthquake_potential_suitability.ipynb | Generates earthquake potential suitability layer | 
| build_nonattainment_suitability.ipynb | Generate non-attainment suitability layers | 
| build_population_suitability.ipynb | Generate proximity to population dense areas suitibility layers | 
| build_railnodes_navwaters_suitability.ipynb | Generate proximity to rail nodes and navigable waters suitability layers |
| build_slope_suitability.ipynb | Generate slope suitability layers |
| build_solar_suitability.ipynb | Generate solar suitability layers | 
| build_water_suitability.ipynb | Generate water availability suitability layers | 
| build_wind_suitability.ipynb | Generate wind suitability layers | 
| validation.ipynb | Run validation for non-renewable technologies | 
| validation-solar.ipynb | Run validation for solar PV | 
| validation-wind.ipynb | Run validation for wind | 
