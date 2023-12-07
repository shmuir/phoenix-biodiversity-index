# Change in Biodiversity Intactness Index in Phoenix, AZ 2017-2020

A project for EDS220: Working with Environmental Datasets for the Masters of Environmental Data Science Program at UCSB. 

The goal of the project is to gain experience working with and mapping spatial data in Python. In this notebook, I obtained BII data for 2017 and 2018 from the Microsoft Planetary Computer (MPC) STAC and found areas with a high BII that were lost from one year to the next. This analysis is for Phoenix, AZ in particular as Phoenix has experinced a high rate of urbanization in recent years, which puts stress on ecosystems. 

Steps of analysis:

1. Accessing BII data from MPC and reading in Phoenix census data
2. Mapping the geographical context of the study area
3. Finding the percent area that had a BII of 0.75 or higher for 2017 and 2020
4. Finding the difference in high BII area from 2017 to 2020
5. Plot the BII for 2020, showing the high BII areas that were lost since 2017

## Citations
Data was obtained from:

[Microsoft Planetary Computer Data Catalog](https://planetarycomputer.microsoft.com/catalog)

[U.S. Census TIGER Shapefiles](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions)

## File Structure

      phoenix-biodiversity-index  
       │   README.md  
       │   phoenix_biodiversity.ipynb      
       │
       └───tl_2022_04_cousub
            │   tl_2022_04_cousub.shp   #census shapfiles
            

