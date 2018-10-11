# Drivetrain Reliability Collaborative (DRC)
A multipronged research program supported by the U.S. Department of Energy at Argonne National Laboratory and the National Renewable Energy Laboratory (NREL) is examining the causes of main bearing micropitting wear and axial (or "white etch") cracks in wind turbine gearbox bearings. As part of this research program, NREL has instrumented a commercial drivetrain, installed it in a wind turbine at the National Wind Technology Center (NWTC), and has operated it since January 2018. Hundreds of data sets have been acquired in normal power production conditions, as well as transient events such as startups, shutdowns, emergency stops and grid events. This purpose of this GitHub page is to make available these data sets.

Authors: Jonathan Keller and Latha Sethuraman\
mailto :<Jonathan.Keller@nrel.gov> 

# Data Format
The data is stored in .h5 format, a hierarchical data file (hdf) format. 
* For viewing, HDFView2.9 or later is available (https://www.hdfgroup.org/downloads/hdfview/). 
* For processing or analysis of the data, h5 files can be imported into MATLAB (https://www.mathworks.com/help/matlab/ref/h5read.html), Python (install h5py http://docs.h5py.org/en/stable/build.html and get data using pandas dataframe), or R (to access HDF5 files in R, use the rhdf5 library which is part of the Bioconductor suite of R packages).

# Data Documentation and Other References
* Research program (http://www.nrel.gov/docs/fy17osti/67523.pdf). 
* Gearbox and instrumentation (http://www.nrel.gov/docs/fy18osti/70639.pdf).
* Main bearing and instrumentation (http://www.nrel.gov/docs/fy18osti/71692.pdf). 
* Turbine and instrumentation (http://www.nrel.gov/docs/fy15osti/63679.pdf). 
* First wind-season tests and data (http://www.nrel.gov/docs/fy18osti/71529.pdf)

# Acknowledgments
This work was supported by the U.S. Department of Energy (DOE) under Contract No. DE-AC36-08GO28308 with the National Renewable Energy Laboratory. Funding for the work was provided by the DOE Office of Energy Efficiency and Renewable Energy, Wind Energy Technologies Office. This work was also made possible by the contributions of SKF GmbH under Cooperative Research and Development Agreement (CRADA) CRD-16-608, Flender Corporation under CRADA CRD-17-694, and SKF USA under CRADA CRD-17-702.
