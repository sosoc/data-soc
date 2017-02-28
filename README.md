# sync-soc
Resources for obtaining / using ocean colour files

## Downloading files

Core tools the 

* **file search**: https://oceandata.sci.gsfc.nasa.gov/search/file_search.cgi
* **file getter**: https://oceandata.sci.gsfc.nasa.gov/cgi/getfile/

## Reading files

SEADAS, Panoply, etc. 

GDAL

- will read any L1, L2, or L3-SMI file (though georeferencing is not relevant at L2 or below)
- cannot read L3Bin https://trac.osgeo.org/gdal/ticket/6551

R

- `raster` package will provide the same via GDAL 
- `rhdf5` package provides data frames from L3bin (see `mdsumner/roc`)

Python

- 
- 

