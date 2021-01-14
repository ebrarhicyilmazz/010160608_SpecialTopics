# Special Topics in Remote Sensing Personal Homework
## 010160608 - Ebrar HİÇYILMAZ

Within the scope of this project, a baseline has been created for the determination of watery regions using NDWI (Normalized Difference Water Index). This index was also used to examine the changes in water bodies such as floods. In this Project some libraries imported. These are;
- numpy
- rasterio
- matplotlib
- notebook

```python 
  import rasterio
  from rasterio import plot
  import matplotlib.pyplot as plt
  import numpy as np
  %matplotlib inline
```

The NDWI Formula is shown below:

### NDWI=(Band3-Band5)/(Band3+Band5)

#### Band 3=Green , Band 5=NIR

## Inputs
Landsat 8 satellite image for B3(Green)

Landsat 8 satellite image for B5(NIR)

## Outputs
ndwi_ebrar_010160608

## Used index in project
Normalized Difference Water Index (NDWI)

## References
_Szabó, S., Gácsi, Z., & Balázs, B. (2016). Specific features of NDVI, NDWI and MNDWI as reflected in land cover categories. Landscape & Environment, 10(3-4), 194-202. 10.21120/LE/10/3-4/13._ 

_https://en.wikipedia.org/wiki/Normalized_difference_water_index_

_https://www.youtube.com/watch?v=dw2aNRvC5Ts&t=1157s_ 

__Thanks For Your Attention!__


![ITU_LOGO](itu-logo.png)
