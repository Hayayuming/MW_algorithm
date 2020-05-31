# MW_algorithm
Matlab code for the retrievals of SPM and its associated uncertainties

This module provides a package of Matlab functions to derived SPM and associated uncertianties from field measurement of remote sensing reflectance at any spectral resolution or radiometer sensor. This is likely not the fastest implementation possible for the MW algorithm. However, it is easy to use and handles the processing of either multispectral and hyperspectral remote sensing reflectance data. 


# Setting the input data 

To make easier the understanding of the algorithm package, a sample of water-leaving reflectance (RW) its standard deviation, wavelengths, and  field meadured SPM was set: sample_data.mat 


Because radiometric field measurements are most likely to be made available as water-leaving reflectance (RW) we suggest the use of the function 'RW2rrs.m' to convert the measured water-leaving reflectance (RW) to below water remote sensing reflectance (rrs). 

In sequence the inputs necessary for for the main function 'MW_algorithm.m' are the ranges of shape parameters (S and Y) and the mass-specific coefficientes (a_nap at 443 nm, a_nap at 750 nm, and b_bp at 700 nm), the temperature at which RW was measured, and the saturation threshold (Q_filter)

# Questions and SUggestions

For questions regarding the script implementation or to suggest changes to improve its functionality, please contact. juliana.tavora@maine.edu
