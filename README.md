## Code for 

![graphical abstract drawio](https://github.com/der-knight/ILSM/blob/main/Images/graphical%20abstract.jpg)
This is the repository of the India Landslide Susceptibility Map.  
The Input Data Prep includes code for data preparation after data is acquired. 
The models file includes models loading and ensemble generation, and the output_prep includes code for data postprocessing and data vizualization  
The data for the model used can be obtained from source  
## The Raw Tiff files can be obtained from:
ILSM probability https://bit.ly/3ibptIP  
ILSM class https://bit.ly/3IidXGn  
## The Google Earth Engine code for ILSM
````
var ILSM_class= ee.Image("projects/ee-nirdeshsharmanith1/assets/ILSM")  
var ILSM_probability=ee.Image("projects/ee-nirdeshsharmanith1/assets/ILSM_probability")  
````
