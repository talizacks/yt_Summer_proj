# **Dataset**: MERRA-2 
*data retrieval url/method*:
 - https://disc.gsfc.nasa.gov/datasets?page=1&source=Models%20MERRA-2
 - Description/READ_ME doc: https://goldsmr5.gesdisc.eosdis.nasa.gov/data/MERRA2_DIURNAL/M2TUNPUDT.5.12.4/doc/MERRA2.README.pdf

**summary**: The second Modern-Era Retrospective analysis for Research and Applications (MERRA-2) is a
NASA atmospheric reanalysis that begins in 1980. It replaces the original MERRA reanalysis (Rienecker et al., 2011) using an upgraded version of the Goddard Earth Observing System Model, Version 5 (GEOS-5) data assimilation system. MERRA-2 includes updates to the model (Molod et al., 2012; 2014) and to the Global Statistical Interpolation (GSI) analysis scheme of Wu et al.(2002). Details of the MERRA-2 system, including major changes from the MERRA system, are
detailed in the companion GMAO Office Note No. 10. The major motivation for replacing MERRA with MERRA-2 is the fact that the MERRA data assimilation system was frozen in 2008 and is not capable of ingesting several important new data types: as the older satellite instruments fail, the number of observations available for assimilation in MERRA is decreasing rapidly.
MERRA-2 uses GEOS-5, Version 5.12.4, which is able to use the newer microwave sounders and hyperspectral infrared radiance instruments, among other instruments. McCarty et al. (2015)
describes the MERRA-2 observing system

- *keywords*: #GSFC #Earth Sciences #Merra
- *Metadata_Conventions*:
- *creator_name*: NASA GSFC Earth Sciences
- *creator_url*:
- *creator_email*:
- *institution*: GSFC Code 610.2/Global Modeling and Assimilation Office
- *acknowledgment*: 
- *document/dataset history*: READ_ME doc Revisions:

| Date | Changes | Author |
| ---- | ---- | ----------- |
| 08/01/2017 | Updated the document links based on the new UUI web site| D. Ostrenga |
| 09/01/2020 |Updated DOI table, data services, and options for reading data | D. Ostrenga, S. Shen |
| 03/01/2021 | Revise variable table for M2C0NXASM, added tables M2C0NXCTM and M2C0NXLND, updated help-desk email | S. Shen |



**Dataset Variables**:
- *dimensions(sizes)*: 
    - longitude=576, latitude=361, level=72, time=4
- *variables(dimensions)*:
    - Frequency: 6-hourly from 00:00 UTC (instantaneous)
    - Spatial Grid: 3D, model-level, full horizontal resolution
    - Granule Size: ~831 MB
 
| Name | Dim | Description | Units |
| ---- | ---- | ----------- | ----- |
| DELP | tzyx | Layer pressure thickness | Pa |
|O3 | tzyx | Ozone mixing ratio |kg kg-1|
|PS |tyx | Surface pressure | Pa |
| QV| tzyx| Specific humidity |kg kg-1|
|T |tzyx |Air temperature |K|
|U |tzyx |Eastward wind component |m/s|
|V |tzyx |Northward wind component |m/s |


- *other* (units,direction,positive,etc.):