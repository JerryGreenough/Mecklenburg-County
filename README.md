# Mecklenburg-County
An exploration of the geometry of Mecklenburg County in North Carolina using Python. 

<p align="center">
    <img src="https://raw.githubusercontent.com/JerryGreenough/Mecklenburg-County/master/mecktracts.png" width="400" height="400">  
</p>

<p align="center">
    <strong>Cencus tracts for Mecklenburg County, NC</strong>
</p>

Mecklenburg County in North Carolina has a population of 1,077,311 (as of 2017). It is home to the city of Charlotte in addition to smaller towns/municipalities such as Pineville, Matthews, Mint Hill and Huntersville.

The functionality presented here is the fruit of work required to determine and then use GeoJSON data representing county and cencus tract boundaries in North Carolina. It serves as a foundation for further exploration of data related to Mecklenburg County as well as other counties in North Carolina. The ultimate objective is a graphical representation of population figures, life expectancy estimates as well as additional data (based on census tracts) that are provided by CDC.

The work presented here is contained in a Jupyter notebook.

Please ensure that the Python libraries geopandas and matplotlib are installed prior to running the code. Please see the following links for details: 

https://matplotlib.org/3.1.1/users/installing.html

https://geopandas.org/install.html

The GeoJSON data for the geometry of cencus tracts of North Carolina is contained in cb_2018_37_tract_500k.json. This file is large and has been compressed into a .zip file.

<h2>Acknowledgments</h2>

Much of the data used for this project has been made available by Eric Celeste.
Eric Celeste's website is: https://eric.clst.org/tech/usgeojson

Also, data has been sourced from the Cartographic Boundary Files supplied by the United States Census Bureau.
https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html
