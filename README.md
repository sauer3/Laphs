# NEON RSDI 2018 Capstone Project
## Harvard Forest Species Identification

LaPHS = Lidar and PhenoCam Hyperspectral Synthesis 

* Christopher Kilner      christopher.kilner@duke.edu
* Adam Young              Adam.Young@nau.edu
* Victoria Scholl         victoria.scholl@colorado.edu
* Stephanie Auer          stephanie.auer@gmail.com
* Bijan Seyednasollah     bijan.s.nasr@gmail.com

July 14, 2018 NEON Data Institute

Our group wrote a collection of code to derive features from NEON Airborne Observation Platform (AOP) data and combine 
them with species labels from the NEON Woody Vegetation Structure in-situ product. 

The final python jupyter notebook *(Code/LaPHS_workflow.ipynb)* does the following: 

1. Read and clean NEON hyperspectral data
2. Calculate various spectral indices
3. Perform Principal Component Analysis
4. Read the lidar-derived Canopy Height model 
5. Combine spectral and strucural features 
6. (in progress) Train a supervised classifier to predict species 

The Woody Vegetation Structure processing is done in a separate R code file (*Code/calculate_woody_veg_locations.R*) since it 
utilizes NEON code packages written in R. 
