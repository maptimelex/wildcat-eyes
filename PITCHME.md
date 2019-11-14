---?image=assets/images/geo_depart.png&size=50%

---
# Wildcat Eyes



---?image=assets/images/wildcat-eyes-logo.jpg&size=90%

---?image=assets/images/terrabytes27.gif
<div style="background-color: rgba(0,0,0,0.4);width:100%;margin: 0 auto;padding:20px 0px;box-shadow: 0 0 80px ;border-radius: 8px;"> 
<h2>Lidar point clouds</h2>
<h3>46,105 tiles in Kentucky</h3>
<h1>> 20TB</h1>
</div>

---?image=assets/images/usgs.png
<div style="background-color: rgba(0,0,0,0.4);width:100%;margin: 0 auto;padding:20px 0px;box-shadow: 0 0 80px ;border-radius: 8px;"> 
<h2>KY leads the way</h2>
[KyFromAbove](http://kyfromabove.ky.gov/)
</div>


---
<iframe src="https://www.outrageGIS.com/pointclouds/johnson" width="100%" height="600px"></iframe>

---?image=assets/images/dir.gif
<div style="background-color: rgba(0,0,0,0.4);width:100%;margin: 0 auto;padding:20px 0px;box-shadow: 0 0 80px ;border-radius: 8px;"> 
<h3>[ftp://ftp.kymartian.ky.gov](ftp://ftp.kymartian.ky.gov/)</h3>
</div>



---
## Reqs
@ul
- Python 3
    - subprocess, urllib, and zipfile
- For point clouds (on WinOS)
    - LASTools [laszip.exe](ftp://ftp.kymartian.ky.gov/kyaped/LAZ/laszip.exe)
    - Potree point cloud renderer [PotreeConverter.exe](https://github.com/potree/PotreeConverter/releases/tag/1.6)
- Tile index [grids](https://github.com/maptimelex/wildcat-eyes/tree/master/assets/data)
- QGIS
@ulend

---?image=assets/images/q03.png&size=80%

---?image=assets/images/q04.png&size=80%

---
### List of files
```python
data_names = [
"ftp://ftp.kymartian.ky.gov/kyaped/DEMs_5FT/N115E318_DEM.zip",
"ftp://ftp.kymartian.ky.gov/kyaped/DEMs_5FT/N115E319_DEM.zip",
"ftp://ftp.kymartian.ky.gov/kyaped/DEMs_5FT/N115E320_DEM.zip",
"ftp://ftp.kymartian.ky.gov/kyaped/DEMs_5FT/N115E321_DEM.zip"]
```

---
## Jupyter Notebook
* [Windoze](windows-version.ipynb)
* [macOS/Linux](macos-version.ipynb)

---
### Set data dirs
```python
# Populate project folder with asset folders
downloads = f'{root}/{project}/downloads'
lidar = f'{root}/{project}/lidar'
naip_year = f'{root}/{project}/{year}'
dem = f'{root}/{project}/dem'

# Create folders
folders = [f'{root}/{project}', downloads, lidar, naip_year, dem]
for folder in folders:
    subprocess.run(f'mkdir {folder}', shell=True, stdout=subprocess.PIPE)
    print(f"mkdir {folder}")
```


