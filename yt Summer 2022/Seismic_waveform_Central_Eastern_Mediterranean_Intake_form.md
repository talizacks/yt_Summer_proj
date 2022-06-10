# **Dataset**:Dataset for Seismic waveform tomography of the Central and Eastern Mediterranean upper mantle
*data retrieval url/method*:https://zenodo.org/record/3732981#.YpkUi5PMK3I

**summary**:Dataset corresponding to the Seismic waveform tomography of the Central and Eastern Mediterranean upper mantle

This dataset belongs to the seismic waveform tomography of the Central and Eastern Mediterranean by Blom, Gokhberg and Fichtner, Solid Earth (Discussions), 2019. Seismic tomography is an inverse problem where the internal elastic structure of the Earth (the upper ~500 km) is determined from seismograms (the vibrations of the Earth as a result of earthquakes, as recorded by seismometers at the Earth's surface). This inverse problem is cast as an optimisation where the misfit between observed and synthetic seismograms is minimised: waveform tomography (often referred to as full waveform inversion or FWI). Synthetic seismograms are produced by simulating the elastic wavefield of earthquakes within the Earth. The optimisation problem is solved by iterative, deterministic, gradient-based inversion. Gradients are computed using the adjoint method, which requires one forward wavefield simulation and one adjoint wavefield simulation per earthquake used in the project.

The inversion was carried out over several frequency bands, starting with the longest periods and including a progressively broader frequency band. Within each frequency band, ~10-20 iterations were carried out, totalling to a hundred iterations. Synthetic seismograms and iteration information are stored for a subset of iterations, notably those where human interaction (i.e. the selection of events / data windows) took place.

Here, we describe:

The contents of this package
How to set up the package such that all the data can be accessed and used, and reproduce the figures.
Contents of this package

Data that was used for the seismic waveform inversion: raw and processed seismograms, station information, earthquake information, as well as the window selection (designating the parts of the data that were actually used at each stage in the inversion) and synthetic seismograms produced during various stages of the inversion. This information is gathered in the LASIF project "EMed_full.complete.tar".
Models and misfit development across the iterations, as well as models relating to model testing, as carried out after the inversion. This information is gathered in the tarball "MODEL_FILES.tar". Model files are both given in the ses3d ascii format (text file drho, dvsv, dvsh, dvp and block_x, block_y,  block_z) and in bundled .vtu format. Conversion to .vtu was done using the tools in SCRIPTS. These vtu files can be viewed using Paraview.
information on the tools and code that was used to do the inversion:
ses3d: a seismic wave propagation spectral element code in spherical coordinates. This will run both forward and adjoint simulations. This is available publicly through the developers on https://cos.ethz.ch/software/production/ses3d.html. See Gokhberg & Fichtner, 2016.
LASIF: a waveform inversion workflow managing package, where we have made small adaptations to make it suitable for our workflow. The original package is available via www.lasif.net and on github (see Krischer et al, 2015), the modified version is added to this package as 'LASIF-master.zip'.
LASIF_scripts: bespoke scripts in order to interact with the LASIF project and generate different types of analyses and plots that are used in the publication. This is included in the tarball 'LASIF_scripts.tar'
SCRIPTS: containing some modified tools that were originally written for ses3d, as well as some additional tools - notably to interact with models converted to the VTK format. This is included in the tarball 'SCRIPTS.tar'
A description of the conda environment named lasif_ext (which is used for all the data analysis), in the form of the yml file 'lasif_ext.yml'
An additional LASIF project which is used just to compute sensitivity kernels for different windows within the same trace: 'EMed_window_kernels.tar'. This is used as an example in one of the manuscript figures.

- *keywords*:seismic tomography, waveform tomography, seismograms, synthetic seismograms, seismic tomography model
- *Metadata_Conventions*:
- *creator_name*: Blom, Nienke Alexandra; Gokhberg, Alexey;  Fichtner, Andreas
- *creator_url*: 
- *creator_email*:
- *institution*:
    - Institute for Biomedical Engineering (Switzerland)
    - ETH Zurich (Switzerland)
    - University of Cambridge
- *acknowledgment*: 
    - Grants: European Commission:
        CSEM - The Collaborative Seismic Earth Model Project (714069)
- *document/dataset history*:



**Dataset Variables**:
- *dimensions(sizes)*: 
    - ...
- *variables(dimensions)*:
    - ..
- *other* (units,direction,positive,etc.):