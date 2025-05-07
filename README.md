# Karten mit Python erstellen

Credits to *https://github.com/symmy596/towards-data-science-articles*
 

| Thema | Region | Datenquellen |
|-------|-----|---------|
| Topographie | Deutschland | [USGS - GMTED2010](https://www.usgs.gov/coastal-changes-and-impacts/gmted2010) |
| Bevölkerung | Europa | 123 |
| Emissionen | Weltweit | [EDGAR - Emissions Database](https://edgar.jrc.ec.europa.eu/dataset_ghg2024) |
| Wälder | Europa | 123 |

---

### Library
#### Allgemeine
- numpy
- matplotlib

#### Geo libraries
- geopandas
- rasterio
- cartopy
- Shapely 
- earthpy

---

## Anaconda Umgebung vorbereiten
### Anaconda prüfen & aktualisieren

> <span style="color:blue">conda info</span> | *Verify Conda is installed, check version number*

> <span style="color:blue">conda update -n base conda</span> | *Update Conda to the current version*

> <span style="color:blue">conda update anaconda</span> | *Update all packages to the latest version of Anaconda*

</br>

### Virtuelle Anaconda Umgebung vorbereiten

> <span style="color:blue">conda create --name pythonmaps python=3.12</span> | *Virtuelle Umgebung mit dem Namen "pythonmaps" mit der Python-Version 3.12*

> <span style="color:blue">conda activate pythonmaps</span> | *Conda virtuelle Umgebung aktivieren*

> <span style="color:blue">conda install conda-forge::geopandas</span> | *Beispiel für die Installation einer Library*

---

[Topographie Deutschlands mit Python](https://github.com/GeowazM/python-maps/blob/master/topographie/germany.png)
![alt text](https://github.com/GeowazM/python-maps/blob/master/topographie/germany.png)

[Karte der CO2 Emissionen erstellt mit Python](https://github.com/GeowazM/python-maps/blob/master/emissionen/raw6.png)
![alt text](https://github.com/GeowazM/python-maps/blob/master/emissionen/raw6.png)

[Visualising the World’s Carbon Dioxide Emissions with Python](https://towardsdatascience.com/visualising-the-worlds-carbon-dioxide-emissions-with-python-e9149492e820)
![alt text](https://github.com/symmy596/towards-data-science-articles/blob/master/CO2_Emissions/Outputs/raw8.png)

[Creating Beautiful River Maps with Python](https://towardsdatascience.com/creating-beautiful-river-maps-with-python-37c9b5f5b74c)
![alt text](https://github.com/symmy596/towards-data-science-articles/blob/master/Africa_Rivers/Outputs/raw3.png)

[Terraforming Mars with Python](https://medium.com/towards-data-science/terraforming-mars-with-python-4c21ed75117f)
![alt text](https://github.com/symmy596/towards-data-science-articles/blob/master/Mars/Outputs/raw11.png)

[Creating Beautiful Population Density Maps with Python](https://medium.com/towards-data-science/creating-beautiful-population-density-maps-with-python-fcdd84035e06)
![alt text](https://github.com/symmy596/towards-data-science-articles/blob/master/Population/Outputs/raw3.png)

[Mapping the World’s Flight Paths with Python](https://medium.com/towards-data-science/mapping-the-worlds-flight-paths-with-python-232b9f7271e5)
![alt text](https://github.com/symmy596/towards-data-science-articles/blob/master/Forests/outputs/raw4.png)
