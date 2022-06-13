# **Dataset**:Hurricane Dataset for Deep-Hurricane-Tracker model

*data retrieval url/method*:https://library.ucsd.edu/dc/object/bb94252168/_1_1.png/download

*citation*: Kim, Sookyung (2020). Hurricane Dataset for Deep-Hurricane-Tracker model. In Lawrence Livermore National Laboratory (LLNL) Open Data Initiative. UC San Diego Library Digital Collections. https://doi.org/10.6075/J0862DZ8


**summary**: 'We use 20-year-long records from 1996 to 2015 of Community Atmospheric Model v5 (CAM5) dataset. It contains snapshots of the global atmospheric states for every three hours (1 timestep = 3 hours). Each snapshot contains multiple physical variables among which we use the six most important climate variables to define hurricane from scientific literature, such as PSL (Sea level pressure), U850 (Zonal wind), V850 (Meridional wind), PRECT (Precipitation), TS (Surface temperature), QREFHT (Reference high humidity) by order. From global scaled CAM5 reanalysis data, we only used data for the region around the Northern hemisphere which is 180 degree to 340 degree longitude and 0 degree to 60 degree latitude. For the purpose of training proposed tracking model, we fixed time length as 10 (which is 30 hours long). The input image size is 128 times 257 pixels with around 0.50 degree (around 50.0 km) resolution. Basically, the file contains multiple spatio-temporal hurricane data (video) channeled by 6 climate variables with time length 10. All climate variables are normalized between 0 and 1 accordingly (each channel has max value as 1 and min value as 0).'

- *keywords*:Artificial intelligence (AI), Climate AI, Climate change, Climate science,Neural networks, Scientific machine learning, Northern Hemisphere
- *Metadata_Conventions*:
- *creator_name*: Kim, Sookyung
- *creator_url*:
- *creator_email*: jh502125@gmail.com, kim79@llnl.gov, sookyungkim@lbl.gov
- *institution*: Lawrence Livermore National Laboratory
- *acknowledgment*: (Funding) Earth System Grid Federation (ESGF) Project and Task used for working with this data: 40128 / SCW1480-ESGF.

 
- *document/dataset history*:
    - Creation Date: 2018-09
    - Date Issued: 2020
    - Last Modified: 2020-10-26

*Data format*: numpy array
*Original Data source*: https://www.earthsystemgrid.org/dataset/ucar.cgd.ccsm4.cam5.1.amip.1d.002.html


**Dataset Variables**: 

*“hurricaneimagetrain.npy”, “hurricaneimagetest.npy”*:
- *dimensions(sizes)*: Axis; Description; Size
    - 0; Number of hurricane videos; 87837
    - 1; Time; 10 (=30 hours)
    - 2; Width; 128 (= 64 degree = 6400 km)
    - 3; Height; 257(= 128.5 degree = 12850 km)
    - 4; Climate variables; 6 ['PSL', 'U850', 'V850', 'PRECT', 'TS', 'QREFHT']
- *variables(dimensions)*:
    - (3408, 10, 128, 257, 6)
- *other* (units,direction,positive,etc.):

*“hurricanelabeltrain.npy”,“hurricanelabeltest.npy”*:

- *dimensions(sizes)*: Axis; Description; Size
    - 0; Number of hurricane heatmap; 87837
    - 1; Time; 10 (=30 hours)
    - 2; Width; 128 (= 64 degree = 6400 km)
    - 3; Height; 257(= 128.5 degree = 12850 km)
    - 4; Climate variables; 1 (Pixel-level probability that hurricane exists on that location: value between 0~1)”:
- *variables(dimensions)*:
    - (3408, 10, 128, 257, 1)
- *other* (units,direction,positive,etc.):
