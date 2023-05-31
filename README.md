## _Undergraduate-Thesis_

# Analysis of The Level of Risk of K3 Disturbance in Forest Management Activities Using The Remote Sensing Approach at The RPH Takokak, KPH Sukabumi, West Java Province
**Azelia Dwi Rahmawati**
<br /> _Department of Forest Management, Faculty of Forest and Environment, IPB University_

## Research Overview <img src="https://github.com/azeliadr/UndergraduatedThesis/blob/e63627426f1a80cd39aff74285cfc89b616b0d32/GAMBAR/LOKASI%20PENELITIAN%20FIX.png" align="right" width="50%" />
_**Abstract**_: Indonesia's forests are known to have a high wealth of biological resources and play an important role in human life, so they need to be managed sustainably. Sustainable forest management does not only pay attention to aspects of work productivity but demands attention to the welfare of managers/workers and the protection of Occupational Safety and Health (OSH). The utilization of technology with a remote sensing approach can provide information about sources of hazard by using geospatial data as a preventive measure in reducing the number of work accidents. This study aims to analyze the level of risk of OSH disturbance in forest management activities using a remote sensing approach at RPH Takokak, KPH Sukabumi. Six sources of hazard are used as parameters, namely slope, altitude, rainfall, soil type, vegetation density, and accessibility as well as the level of work accidents which are addressed to forest management stakeholders through the questionnaire method. From the 5 class classifications, it was found that the study location was dominated by class 3 classification or had a moderate level of K3 disturbance risk with an area of 1661.02 Ha or 77.36%, and an area of 0.49 Ha or 0.02% of the total felling plots included in risk class 4 or had a K3 high risk level. It is hoped that the results and recommendations from this study can provide information to Perum Perhutani in managing forest areas, especially risk management at RPH Takokak, and can become a reference for further research.
Keywords: Occupational Safety and Health (OSH), Work Accident, Remote Sensing.

## Methodology
<img src="https://github.com/azeliadr/UndergraduatedThesis/blob/8166360d35055d6d62e8f5c29e3cbc554fe6af7d/GAMBAR/DIAGRAM%20ALIR.drawio%20(2).png" align="center" width="100%" />  
<p align="center"> Gambar 1. Research Flow Chart
 
 * Slope
 
 * Elevasi
 
 * Rainfall
 
 * Type of Soil
 
 * Vegetation Density
 <br /> Normalized Difference Vegetation Index (NDVI)
 <br /> Rouse jr JW, Haas RH, Schell JA,  Deering DW. 1974. Monitoring vegetation systems in the Great Plains with ERTS. NASA Special Publication. 351(1): 309-317.
 ```
   var ndvi = sentinel_2.expression('(NIR - Red) / (NIR + Red)', {
  'NIR': sentinel_2.select('B8'),
  'Red': sentinel_2.select('B4')
 });
 ```
  
 * Accessibility
 
 * Work Accident Rate

## References

 ________________________________________________________________________________________________________________________________________________________
**Azelia Dwi Rahmawati**
<br /> _Department of Forest Management, Faculty of Forest and Environment, IPB University_
<br /> azeliadr@gmail.com azeliadrazelia@apps.ipb.ac.id
