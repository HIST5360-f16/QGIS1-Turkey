![Turkish Flag](https://upload.wikimedia.org/wikipedia/commons/8/87/Flag_of_Turkey.png)
# Turkey-Tutorial
### Author: achmed.foggie@mavs.uta.edu
## QGIS Tutorial (Turkey)

## 1 Make a folder or directory called “Turkey” on your computer.
## 2 Download the following Turkey data sets from DIVA-GIS [Google it] into that directory: Administrative Areas, Roads
* Unzip them; each should be in its own sub-directory.
* TUR_adm
*  TUR_rds

## 3 Open QGIS and set up a new project.
## 4 CRS


![CRS Screenshot](/CRS Screenshot.png)


* Select the settings tab , then select options
* In the new window select CRS on the side of the window
* Enable on the fly
* Select the globe icon on the right
* Type "WGS 84", then select WGS 84/UTM zone 39N

## 5 Add a layer
* First click the layer tab at the top of the screen then Add Layer.
* Select Add Vector Layer
* Select browse, then select TUR_adm0.shp (Make sure it’s a shape file)
* On the left side of the screen in the layers panel select right click on TUR_admin0
* Select style, simple fill and then under fill style select no brush
* Press OK

## 6 Repeat steps for TUR_admin1.shp

![Layers Screenshot](/Layers Screenshot.png)

## 7 Add the TUR_roads layer
* Right click on the layer in the layer panel
* Go to Properties the select the style tab
* Change the color to make it easier to see
* Change the width to 1.00000

## 8 Add Maps
* Select the Layer tab, then select "Add Raster Layer"
* Select Turkey Map 1.0 (I have already geo-referenced this file.)
* Move the TUR_admin0 and TUR_admin1 layers up so they visible.
* Repeat steps for Turkey Map 2

    Save your work. Close QGIS
