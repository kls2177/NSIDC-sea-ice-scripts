# NSIDC-sea-ice-scripts

This repo contains scripts to manipulate NSIDC daily sea ice data (Bootstrap or NASA Team). 

Starting from dowloaded .bin files from the NSIDC ftp site, the scripts incorporate in-house NSIDC IDL and Fortran code to convert
to .nc files, to linearly interpolate the 1979-1987 semi-daily observations to daily and to convert from polar sterographic grids 
to lat-lon grids.
