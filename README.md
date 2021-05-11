# Blackfoot-Reservoir-Volcanic-Field Gravity Data

[![DOI](https://zenodo.org/badge/365883125.svg)](https://zenodo.org/badge/latestdoi/365883125)

Repository for data and work related to the Blackfoot Reservoir Volcanic Field.

## Datafile descriptions

All the data collected by the University of South Florida has been reduced to a base station in the town of Soda Springs, ID. The corrections made to the data include the latitude (theoretical), atmospheric, free-air, spherical cap Bouguer, and terrain correction, and are present within the datafiles. The Bouguer and terrain corrections were made assuming an average crustal density of 2670 kg m<sup>-3</sup>. The tidal and drift corrections are tied into the observed gravity measurement in the datafiles. The marine data has additional corrections (Eotvos and platform response) that are tied up in the observed gravity measurement within the datafile. These corrections are made to compensate for the motion of the gravimeter in relation to the rotational axis of the Earth as well as the motion of the platform in response to tilting from wave action. The marine data was collected and processed with the help of Nigel Brady of [Dynamic Gravity Systems (DGS)](https://www.dynamicgravitysystems.com/)

The USGS data was reprocessed using the same corrections for the data that USF collected, and tie in points were used to shift the anomaly values to be consitent with the USF data.

All the data is stored as space-separated text files, and the UTM Zone for all these data points are Zone 12T.

<b>blkft2021_gravity.dat</b> - Compilation of all the datafiles in this repositiory. 

<b>usf+usgs_2018.dat</b> - Compilation of USF surveys prior to 2019 and the USGS data. 

<b>usf_terrestrial_092019.dat</b> - Data collected on land in September of 2019

<b>usf_marine_092019.dat</b> - Data collected on the Blackfoot Reservoir. 

<b>usgs_reprocessed_2020.dat</b> - Reprocessed USGS data shifted to the USF data. Provides larger spatial extent than the USGS data in the usf+usgs_2018.dat datafile.
