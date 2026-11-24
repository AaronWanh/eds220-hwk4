# Using false color imagery to visualize Palisades and Eaton

## About: 
The goal of this notebook is use the satellite imagery to visualize the regions that were affected by the Palisades and Eaton fire using both true color and false color imagery. Using the perimeter geospatial datasets we can use create a boundary around the perimeter of the affected regionst to confirm.

<img width="517" height="386" alt="images" src="https://github.com/user-attachments/assets/4d621ae9-7d96-4fd5-8253-4a7c2230f7d7" />

## Repository Structure:

This repository contains a data folder that holds geopackage files of both perimeters of the Palisades and Eaton fires. It also houses the Landsat 8 satellite data needed to use color imagery to visualize the fire burn scars. However we have a gitignore file to prevent the large dataset from bloating the repository. The main code and graphs are within the Jupyter notebook hwk4-task2-false-color-Wang.ipynb. Finally the README.md file is a summary of what is contained inside the repository and what it accomplishes. 

```text
|   .gitignore
|   hwk4-task2-false-color-Wang.ipynb
|   README.md
|   
\---data
        Eaton_Perimeter_20250121.geojson
        landsat8-2025-02-23-palisades-eaton.nc
        Palisades_Perimieter_20250121.geojson
```

## Data:
The data is housed in the data folder called 'data' and in order to run the notebook, you will need to download all the data files. 


## Citations:
* Microsoft planetary computer. (2024). Microsoft.Com. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2
* Palisades and Eaton dissolved fire perimeters (2025). (2025). Arcgis.Com. https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about
