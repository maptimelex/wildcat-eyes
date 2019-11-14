---?image=images/geo_depart.png&size=50%


---?image=assets/images/wildcat-eyes-logo.jpg
## boyd.xyz/409
@color[#444](URL to this presentation)

---?image=https://farm8.staticflickr.com/7669/26770757943_3e76b3921d_h.jpg"
<div style="background-color: rgba(0,0,0,0.4);width:100%;margin: 0 auto;padding:20px 0px;box-shadow: 0 0 80px ;border-radius: 8px;"> 
<h2>Boyd Shearer</h2>
[boydx.github.io](https://boydx.github.io) | [outrageGIS.com](https://outrageGIS.com)
</div>

---
# GEO 409
## Spring 2020 
### T/Tr 3:30–4:45

---?image=i/001.jpg
@quote[Demand for cartographers is projected to grow nearly 30% by 2024.]([Wired Magazine]((https://www.wired.com/tag/cartography))


---?image=images/kamp.png&opacity=10
@quote[In no other time have we had so much access to data.]([David Cater]((https://kampro.org/ky-gis-conference/2019-conference-agenda-and-abstracts/))


---?image=i/terrabytes27.gif
<div style="background-color: rgba(0,0,0,0.4);width:100%;margin: 0 auto;padding:20px 0px;box-shadow: 0 0 80px ;border-radius: 8px;"> 
<h2>Lidar point clouds</h2>
<h3>46,105 tiles in Kentucky</h3>
<h1>> 20TB</h1>
</div>

---?image=images/usgs.png
<div style="background-color: rgba(0,0,0,0.4);width:100%;margin: 0 auto;padding:20px 0px;box-shadow: 0 0 80px ;border-radius: 8px;"> 
<h2>KY leads the way</h2>
[KyFromAbove](http://kyfromabove.ky.gov/)
</div>

---
## What can you do with point clouds?
massively dense collections of (x,y,z) locations

---
![Hike up to Indian Arch](https://www.youtube.com/embed/nFV8ftGN0aM)

---
<iframe src="https://www.outrageGIS.com/pointclouds/johnson" width="100%" height="600px"></iframe>

---?image=https://uky-gis.github.io/support/lidar-arcgis/locate_arch.gif&size=80%

---
<iframe width="100%" height="600px" src="https://bluegrassland.carto.com/builder/50150569-e092-4c28-a67f-eb4bfbc7a50e/embed"></iframe>



---
## Class tools:
@ul[squares]
- ArcGIS Pro
- Python
- GitHub
@ulend





---
## Theme:
## Kentucky
## Y'all!

---?image=https://c1.staticflickr.com/1/390/31713088315_f0326f577c_k.jpg
<h2 style="color:#eee;text-shadow: 2px 2px 4px #000;">Red River Gorge</h2>

---?image=https://farm2.staticflickr.com/1769/42671081904_40c84be780_h.jpg


---
# Quiz
## Where are we?

---?image=https://uky-gis.github.io/support/python-arcgis/pointcloud_extract/cufa.jpg

---?image=images/01/lidar-02.jpg

---
# Python

---
## @color[#444](Data is redundant)
## Code is unique

---
```python
# Make Python script to simulate landscape illumination
# and predict insolation rates.
import arcpy 
azimuth = 90 
while azimuth < 271:
    output = f'c:/output/directory/hillshade_{azimuth}.tif'
    arcpy.Hillshade_3d (in_DEM, output, azimuth, 45)
    azimuth += 5
```

---
![Video](https://player.vimeo.com/video/292571411)


---
## Last but not least...


---
## Resume additions
@ul[squares]
- ArcGIS Pro
- Python
- Big data
@ulend

---
## Thank you!
@color[#444](Keep going to see other class projects)

---?image=images/geo_depart.png&size=50%

---
## Other class projects


---?image=https://farm6.staticflickr.com/5620/31047412341_bf8ece65f4_h.jpg
<h2 style="color:#eee;text-shadow: 2px 2px 4px #000;">Pilot Knob SNP</h2>
<h3 style="color:#eee;text-shadow: 2px 2px 4px #000;">Trail mapping</h3>


---?image=https://farm6.staticflickr.com/5730/30340396284_a169bdc431_o.jpg
<img src="https://farm5.staticflickr.com/4686/24053277287_2a7c9f041a_k.jpg" height="600px">

---?image=https://farm6.staticflickr.com/5730/30340396284_a169bdc431_o.jpg
<iframe src="https://townbranch.carto.com/builder/dbce1cd2-b019-11e6-bd55-0e05a8b3e3d7/embed" width="100%" height="520" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

---
## Pine Mountain SRP
### Scenic Analysis
<a href="http://sweb.uky.edu/~blshea1/nre355/pine-mountain-canopy-tour/" target="blank">LINK</a>

---?image=https://farm6.staticflickr.com/5678/23200804570_7ba220d2d1_h.jpg

---?image=https://farm1.staticflickr.com/576/23495298805_ce5ec0030d_h.jpg

---?image=https://farm1.staticflickr.com/681/22868246864_2fb8e40e79_h.jpg

---
![Video](https://www.youtube.com/embed/TkWMGD8ZDDM)

---
## Discovering
### Town Branch Trail
<a href="https://reece2ke.github.io/geo409_site/index.html" target="blank">LINK</a>

---
#### The team
<iframe width="100%" height="500px" src="https://kuula.co/share/7lLKn"></iframe>

---?image=i/007.jpg
<a href="https://farm3.staticflickr.com/2842/34173538111_a32119a81c_o.jpg" title="Block diagram of downtown Lexington, Kentucky" target="blank">LINK</a>


---?image=images/01/trees.jpg
<a href="http://boydx.github.io/tbt/oblique/" target="blank">LINK</a>



---
## Student observations
### NCAA tournament basketball celebrations
<a href="https://geography.as.uky.edu/sites/default/files/CampusCelebrations_Layout_150508-01.jpg" target="blank">map</a>

---?image=i/10.jpg

---
## Arboretum Woods
### Tree Census
<a href="https://geography.as.uky.edu/sites/default/files/BoydShearer_Lab3_ArboretumWoodsTreeCensus.jpg" target="blank">LINK</a>

---?image=https://geography.as.uky.edu/sites/default/files/BoydShearer_Lab3_ArboretumWoodsTreeCensus_700.jpg


---
## Project link
<a href="https://rvirto01.github.io/NRE355_Tree_canopy_study/" taRGET="BLANK">LINK</a>

---
## Robinson Forest Camp
### trail map
<a href="https://geography.as.uky.edu/sites/default/files/RobinsonForestCamp_TrailMap.jpg" target="blank">map</a>

---?image=https://geography.as.uky.edu/sites/default/files/RobinsonForestCamp_TrailMap.jpg

---?image=https://farm5.staticflickr.com/4175/34413343182_c906452c0b_h.jpg

---
## Fayette County
### Scenic Analysis
<a href="https://geography.as.uky.edu/sites/default/files/SceniicLandscapeIndexFayetteCounty_th.jpg" target="blank">map</a>

---?image=https://farm5.staticflickr.com/4263/35717804616_c71b17d150_h.jpg

---
## Analyzing
### Walkability

---?image=images/01/map-pedshed.jpg

---?image=https://geography.as.uky.edu/sites/default/files/GEO409_2014_FinalProject_Preview.jpg
<h3 style="color:#eee;text-shadow: 2px 2px 4px #000;">Where are the "cow paths" on campus?</h3>
<h4 style="color:#eee;text-shadow: 2px 2px 4px #000;">Are they quicker than sidewalks?</h4>

---?image=http://boydx.github.io/collisions/images/VineStreet_LexingtonKentucky.jpg
<h3 style="color:#eee;text-shadow: 2px 2px 4px #000;">Bike/Pedestrian vs. Car Collision Analysis</h3>
<a href="http://boydx.github.io/collisions/" target="blank">LINK</a>