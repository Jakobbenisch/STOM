This repo contains function for graphs and calculations used in the paper [Can short-term online-monitoring improve the current WFD water quality assessment regime? Systematic resampling of high resolution data from four Saxon catchments](https://www.mdpi.com/2073-4441/16/6/889).
In order to use the functions you need to know that I used nested lists for input data ([[montiroing station]][,parameter]) and output data ([[montiroing station]][[parameter]] sometimes [[year]])

There is a function to simulate according to OGewV:
- STOM (can be quite slow with lots of data and minute resolution!)
- grab sampling
- true value
- a function for editing unify timestamps with different intervalls 

Graphs for:

- linear regression between chloride concentration and electrical conductivity (plot_cl_cond_regression)
- data availability with colors and parameters (plot_available_data)
- heat map for the comparsion between grab sampling and STOM parameters (plot_heat_map) 
