 **Title**: Finite-frequency P, SH, and SV body wave models for the continuous US. Joint body-wave and surface-wave model for the western US.
 **id**: DNA13
**summary**:DNA13 is a 3-D model of shear and compressional velocity perturbations for the continuous US.

*keywords*: seismic tomography, continuous US, shear velocity, compressional velocity, joint inversion
*Metadata_Conventions*: Unidata Dataset Discovery v1.0
*creator_name*:  IRIS EMC
*creator_url*: [http://ds.iris.edu/ds/products/emc/](http://ds.iris.edu/ds/products/emc/)
*creator_email*: products@iris.edu
*institution*: IRIS DMC
*acknowledgment*: 
	Model was created by Robert W. Porritt and Richard M. Allen,  Seismological Laboratory. Dept. Earth and Planetary Science. UC Berkeley
	reference: Porritt, Allen, and Pollitz (2014)
	references: [http://seismo.berkeley.edu/~rallen/pub/2014porritt/data.php](http://seismo.berkeley.edu/~rallen/pub/2014porritt/data.php)

*document/dataset history*:
	- 2014-01-15 model converted to netCDF by IRIS EMC  
	- 2016-04-13 reorganized the parameters
*data retrieval url/method*:
*dimensions(sizes)*: depth(129), latitude(55), longitude(109)
*variables(dimensions)*:
	float32 depth(depth), float32 latitude(latitude), float32 longitude(longitude), float32 vp(depth, latitude, longitude), float32 vsh(depth, latitude, longitude), float32 vsv(depth, latitude, longitude), float32 vsvj(depth, latitude, longitude)
*other*:
	geospatial_lat_min: 25.00
    geospatial_lat_max: 52.00
    geospatial_lat_units: degrees_north
    geospatial_lat_resolution: 0.5
    geospatial_lon_min: 234.00
    geospatial_lon_max: 288.00
    geospatial_lon_units: degrees_east
    geospatial_lon_resolution: 0.5
    geospatial_vertical_min: 0
    geospatial_vertical_max: 1280
    geospatial_vertical_units: km
    geospatial_vertical_positive: down