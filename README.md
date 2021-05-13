# NIH-NASA-Flood-Risk-Analysis
NASA/NIH project on finding risk associated with each healthcare centers of getting affected by flood in USA.

## Data
The data files are obtained from two main sources NASA (National Aeronautics and Space Administration
) and HIFLD (Homeland Infrastructure Foundation-Level Data)

NASA : [GPM (Global Precipitation Measurement) data](https://disc.gsfc.nasa.gov/datasets/GPM_3IMERGHH_06/summary?keywords=GPM%20IMERG%20final)  
[PPS registration and GPM data](https://gpm.nasa.gov/data/directory/imerg-final-run-pps-research-gis) 

HIFLD : [US_Hospitals_data](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals?geometry=107.413%2C-16.829%2C-138.329%2C72.120) 
[US_Urgent_Care_Center_data](https://hifld-geoplatform.opendata.arcgis.com/datasets/urgent-care-facilities)
[US_Pharmacy_and_Dialysis_Center_data](https://hifld-geoplatform.opendata.arcgis.com/datasets/pharmacies)

## Description
The scope of this project is to identify the health care facilities including hospitals, urgent care facilities and pharmacies that are most impacted by extreme rainfall. The exact risk for a healthcare facility getting affected by flood depends on several factors like soil moisture, elevation, precipitation level and many more. Right now, for this project I focused on precipitation level at each healthcare facility only. I applied different models using unsupervised clustering methods and compared the results of each to come at a particular solution.

## Acknowledgement
This project has been completed as a part of Data Analytics course, taught by Prof. Thilanka Munasinghe at Rensselaer Polytechnic Institute, Troy, NY. I would like to thank him for his guidance throughout the project and for giving me this opportunity to work on NASA project. 
