
# Process  : PrepareBuildingData on french cities with BDTopo data source

It is a specialisation of the process PrepareBuildingData on the specific case pf BDTopo source which is adapted to French cities. 

## Step 1: Download Data from Geoservice Web

FR-BDTopo data can be retrieved on different spatial scopes : whole France, region, department. Whole France is very heavy so we identify departments and region that intersect the spatial scope of the map and retrieve either the region or  departments. Data can also be retrieved at different times.    
https://geoservices.ign.fr/bdtopo#telechargementshpdept 
The download contains several files corresponding to the different topographic themes we keep the files BATI which contains building. 

## Step 2: Data Cleaning and Merging

* We load the BATI layers in QGIS
* * Due to version differences in the dataset, the 2011 building data required merging of various building themes. This was accomplished using QGIS and the "Merge Vector Layers" algorithm. This algorithm combines multiple vector layers of the same geometric type into a single layer.

## Step 3: Crop study area 
* We used spatial analysis tools in QGIS to intersect the building layers with the study area defined as a 45mn car isochrones.

## Step 4: Create metadata 
* The BuildingData dataset is ready but won't be shared directly on the git, only references to it and additional metadata. Yet it is important to store it because it is a useful associate data to further work with BuildingEvolution. 
* The associate description can be published either by creating a specific entry for this dataset on the Dataset.md registry, FR-XXXX-FUA-Building-YYYY or by creating directly an identifier for the BuildingEvolution dataset we want to create with the Building data and the Building data is described within the description of the BuildingEvolution provenance.   


