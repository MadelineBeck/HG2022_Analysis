# HG2022_Analysis
Hourglass Data and processing code for M Beck's MSc Work
Madeline Beck’s Thesis Work – File Descriptions
Update Log:
-	20230925: The following files are uploaded to Madeline Beck’s personal OneDrive Folder. However, data still needs to be uploaded or shared with Sproles lab OneDrive. 

•	/Hourglass/Dates: File starting with 2021 -- -- or 2022 -- --. Each folder contains the following folders containing the described data. 
-	Agisoft – contains Agisoft Files used for imagery processing. 
-	20220212 and 20220218 – Folder called Agisoft_Final for final processing and PPK_Compare_Processing for Agisoft files created during image processing comparison
- Deliverables – Final DEM or Ortho .tif files
- 20220212 and 20220218 – Contains Final_Deliverables with final DEM and Ortho and PPK_Deliverables with PPK created DEMs
-	GIS – GIS project and data for Snow Depth calculations and error filtering.
-	Imagery – All flight imagery for each field collection day
-	RTKLIB – Imports and Exports created for PPK Processing
•	/Hourglass/GCPs – csv files containing the locations of GCPs collected for each flight date.
•	GIS_Data_Layers – GIS data layers used for visualization purposes.
-	Bridger_DataLayers – Data layers downloaded or clipped for Bridger Visualization purposes.
-	Bridger_Mtns_Boundary – .shp file data for drawn Bridger Mountains Boundary
-	Bridger_DEM_Clipped.tif – 1/3 arc second DEM clipped for the Bridger Mountain Range
-	Bridger_Hillshade.tif – Hillshade created from above DEM
-	HG_Boundary – .shp file data for drawn Hourglass Boundary
-	MontanaStateBoundary - .shp file data for state of Montana Boundary
-	SNOTEL_Locs – High accuracy position data for Montana SNOTELs and Bridger SNOTELs based on SNOTEL download code
•	PPK_Imagery_Locations – PPK corrected imagery locations based on PPK correction code and no height changes for each flight date
•	SnowDepth_Rasters - .tif files for each flight date with calculated Snow Depth in meters. This data was used in further python code to calculate snow depth histograms for each flight date and SWE datasets based on modeled density. 
•	SnowPilot – SnowPilot data for three days of full-pit profiles collected on March 25, May 05, and May 10 2022. 
•	SWE_Compare_DFs - .csv files containing measured and modeled SWE values for each collected validation point in the meadow for each day of federal SWE sampler collection.
•	SWE_Rasters_VisOnly – Rasters used for visualization purposes and not for processing. 
