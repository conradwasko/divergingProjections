# divergingProjections
Projections of extreme rainfall and streamflow for Australia's hydrologic reference stations (HRS) using CMIP5 (RCP4.5 and RCP8.5) for AEPs of 90%, 80%, 50%, 20%, 10%, 5% and 2% for the time horizons 2036–2065 (nominally centred on 2050) and 2070–2099 (centred on 2085) relative to the historical baseline of 1976-2005.

A detailed description of the methods used to generate this data are provided in: Wasko, C., Guo, D., Ho, M., Nathan, R., Vogel, E., 2023. Diverging projections for flood and rainfall frequency curves. Journal of Hydrology 620, 129403. https://doi.org/10.1016/j.jhydrol.2023.129403

If using this data a citation to the above manuscript would be greatly appreciated.

## Details
This repository contains data for replicating Figures 7-9 in Wasko et al (2023). The zip files contain the percentage changes for each climate model-downscaling pairing for each station, which each file named with the station ID, with "fut1" and "fut2" being the 2050 and 2085 time horizons respectively. The text files contain summaries for each station using the eight best perfomring climate-model downscaling pairs. They contain the median change using all four climate models and the QME and MRNBC bias correction methods. Note that these files also contain the Nash-Sutcliffe Efficiency (NSE) of the hydrologic models used. In the manuscript results use stations which had catchment models with NSE greater than or equal to 0.4.

HRS metadata available from http://www.bom.gov.au/water/hrs/content/hrs_station_details.csv. The raw HRS data can be obtained from http://www.bom.gov.au/water/hrs/. The projections used here were obtained from https://awo.bom.gov.au/.
