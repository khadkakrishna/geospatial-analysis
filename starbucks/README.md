## Starbucks Stores Analysis
 see output-enabled notebook using nbviewer:
 https://nbviewer.jupyter.org/github/khadkakrishna/geospatial-analysis/blob/master/starbucks/Starbucks.ipynb 

 ![starbucks image](data/image2.jpeg){:height="50%" width="50%" }

#### Getting started / dependencies:

```
import math
import pandas as pd
import geopandas as gpd
from geopandas.tools import geocode  
import folium 
from folium import Marker
from folium.plugins import MarkerCluster
from shapely.geometry import Point
```
