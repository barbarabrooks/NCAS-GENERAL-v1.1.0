# NCAS-GENERAL-v1.1.0
This standard applies to 
    1. Profiling instrument where the altitude of the range gate varies over the duration of the file.
    2. The data products: 
        2.1 aerosol-backscatter-radial-winds
        2.2 depolarisation-ratio
        
This standard ONLY applies to profiling instruments where the altitude of the range gates varies over the duration of the file and to the data products erosol-backscatter-radial-winds & depolarisation-ratio

It is for profiling instruments (not the radiosondes). The altitude variable and profile variables have dimensions of time and index.

The version should be used if the altitude variable is likely to vary over the duration of the file.

The data products aerosol-backscatter-radial-winds & depolarisation-ratio are both used in conjunction with the Doppler Aerosol Lidar. 
This is a scanning instrument - and uses index_of_range and index_of_angle to  locate a point in space.

This version also corrects for some CF non-conformities

NCAS-AMOF-1.1 or NCAS-GENERAL-1.1 are accepted when refrencing in file global attributes

For data products associated with 
  1. sondes
  2. non-profiling instruments
  3. profiling instruments where the altitude of the rage gate is constant over the duration of the file use NCAS-General- v2.0: 
    https://github.com/ncasuk/AMF_CVs/tree/v2.0.0rc
