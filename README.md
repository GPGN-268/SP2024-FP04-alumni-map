[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GPGN-268/SP2024-FP04-alumni-map/HEAD)

# SP2024-FP04-alumni-map
## GP100 Alumni Map
## Members: 
Max Ercolani (@MaxErcGP), Renee Fischer (@Renee-Fischer) , Jackson Howard (@jacksonhoward1856)

## Summary: 
For the 100th anniversary of Geophysics at Mines (GP@100) website, we have created maps of where Mines GP almuni are currently living. We also utilized data analysis to describe and understand trends in the data we have of Mines GP alumni.

## Background info:
We were interested in understanding patterns in where alumni take residence following graduation from the Mines Department of Geophysics. We also wanted to understand trends in atributes like graduation year and degree type of GP alumni.

## Objective:
Create a comprehensive map of the current residence of Mines Geophysics alumni, and analyze trends.

## Datasets:
Anonymous records of Department of Geophysics alumni; state and country residence, graduation year, and level of degree obtained.

[GP Alumni List](https://github.com/GPGN-268/SP2024-FP04-alumni-map/blob/6131c6380ba5bcbf34a334e886e667b6c3157e90/data/GP_Alumni_List.csv)

## Tools/packages: 
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/)
- [CartoPy](https://scitools.org.uk/cartopy/docs/latest/installing.html)
- [GeoPandas](https://geopandas.org/en/stable/)
- [GeoPy](https://geopy.readthedocs.io/en/stable/)
- [Shapely](https://shapely.readthedocs.io/en/stable/)
  
##  Methodology/approach:
- Compile alumni data by filtering by state and country.
- Split the compiled state data by level of degree obtained.
- Visualize data with simple graphs.
- Use Python GIS (Geographical Information System) plotting tools to make maps.

## Challenges:
- Cleaning the data so that it can be manipulated easily.
- Transferring data to a visually representative form (map).
- Working with geographical plotting tools.
  
## Outcomes:
- Produced comprehensive maps to visualize GP Alumni distributions geographically.
- Produced various figures visualizing the distribution of graduation rates and degree types.
- This information will be useful as a promotional tool for the geophysics program at Mines.

## Any other relevant information, images/tables, references, etc.:
To respect the privacy and anonymity of alumni, the plotting of residency will be detailed no further than state and level of degree obtained for each alum.

![Global Alumni Map](https://github.com/GPGN-268/SP2024-FP04-alumni-map/blob/main/figures/Global_GP_Alum_Map.png)
![US Alumni Map](https://github.com/GPGN-268/SP2024-FP04-alumni-map/blob/main/figures/US_GP_Alum_Map.png)

## References:
Melinda Gale - Client and Data Acquisition
Previously mentioned packages and libraries
ChatGPT - Debugging
