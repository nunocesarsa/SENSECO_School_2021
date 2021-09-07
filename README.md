# SENSECO_School_2021
Jupyter notebooks and data for the Senseco Summer School, 2021 in Plovdiv, Bulgaria


## Instructions to run "seamlessly"

1. Download zip file, unzip to a folder in your computer.
2. Go to your google drive and create a SENSECO folder (on the root)
  - Copy the contents of the SENSECO folder in your computer to your google drive accordingly 
3. Copy the folder: SENSECO_S2Data to your google drive (on the root)

Confirm the following folder structure on your google drive:

<google drive>/Senseco/Models/

<google drive>/Senseco/Outputs/

<google drive>/Senseco/Shapefiles/ (in this folder, you should make sure all the shapefiles are on it)

<google drive>/Senseco_S2Data/ (this folder should have everything that came with the zip file on it)

- Run the various google colab books following the numerical order


## Otherwise

1. You need to adapt the paths on your scripts to the following folders:

- S2_Responses_S2A.csv - Used to generate Synthetic S2 data

- CLBJ Boundary_Square_Small.shp (et al) - Used to fetch the S2 images in GEE, crop them, and download them to your google drive (provided)

- NEON_DHP_Centroids_UTM14N.shp (et al) - Used to extract the values of LAI and Ch from the final predictions

2. Adapt the numerous locations where the path to a file is used in the loops. These use the filename to fetch the "date" of acquisition for example. 
  
 

