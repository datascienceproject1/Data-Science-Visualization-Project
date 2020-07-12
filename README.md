# Data-Science-Visualization-Project
The repository created for Data Science Visualization Project, to keep version control.

The code has been verified and tested, Master branch is updated with code now. The final instructions to run the code can be seen below.

Before running the script, Download the pre-processed data file. 
It contains:
LatScaled.mat      - the latitude locations for the data grid, scaled appropriately in a single vector.
Lon scaled.mat     - the longitudinal data scaled appropriately in a single vector.
o3Scaled.mat       - the ozone values, scaled appropriately, a 4D array of 7 models x 700 x 400 locations x 25 hours.
Radii.txt          - the appropriate radii for use with the clustering algorithm to process the data provided.


1- Open MATLAB and set folder "Ozone" to the current directory.

2- Open "OzoneVisualize.m" and run.

3- The code will automatically save a GIF named as "OzoneHour.GIF" in current directory.



Note: I have not used 24Hour data file because it has array size of 398x698. Whereas, it the latitude and longitude
of Europe make an array of 400x700. o3Scaled.mat file contains ozone values from all 7 models, for all 400x700 locations
and for 25 hours. That is why this file has been used for visualization.
