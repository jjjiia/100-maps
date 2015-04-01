# 100-maps

html file uses #cityname to load different city data files

cities are lowercase, and uses underscore as space in case of multiple words

datafiles are:
	var csv = "data/"+city+"/"+city+"_income.csv" - from census
	var geojson1 = "data/"+city+"/"+city+"_bg.geojson" - from national repository of shapfiles
	var overlap = "data/"+city+"/"+city+"_overlap.csv" - processed from qgis
	var neighbors = "data/"+city+"/"+city+"_geoid_neighbor_hash.json" - processes from qgis
	var neighborhoods = "data/"+city+"/"+city+"_neighborhoods.json" - from zillow
	
