
## Leaf traits database

###### Two csvs including individuals data and site information data.

###### Data availbility: The individuals data are available from the authors of papers. It is now public available. In case of any issues concerning the observed and predicted data, and for all queries on ancillary information including the climate data, please contact Yunke Peng (yunke.peng@usys.ethz.ch) or Iain Colin Prentice (c.prentice@imperial.ac.uk).


#####For individuals.csv, it has included following measured variables for all individuals data (N = 5000):

* lat: latitude in degree

* lon: lontitude in degree

* Elevation: Elevation in m

* Vcmax.25: Measured maximum rate of carboxylation capacity at 25 degree (umol/m2/s)

* Jmax.25: Measured maximum rate of electron transport at 25 degree (umol/m2/s)

* narea: leaf nitrogen per area (g/m2)

* parea: leaf phosphrous per area (g/m2)

* lma: leaf mass per area (g/m2) 

* o_vcmax: Measured maximum rate of carboxylation capacity at leaf temperature (umol/m2/s)

* year: measurement year

* species: genus species

* o_X: Measured leaf ci/ca ratio

* o_jmax: Measured maximum rate of electron transport at leaf temperature (umol/m2/s)


#####For site_info.csv, it has included climate, soil and environmental data at each site (N=266). The lon and lat in this csv can be perfectly merged with individuals.csv above, to make all invididuals data available in their climate and (a subset of) soil information, which contributed to the relevant analysis in Peng et al. 2021's Paper.

* lon: lontitude in degree
* lat: latitude in degree
* Ca: CO2 concentration (in ppm) at measurement year
* pH: soil pH
* N: soil N content (%)
* CN: soil C/N 
* P_total: total soil P (mg/kg)
* NP: soil N/P
* pft_value: plant functional type value extracted from MODIS (NOT USED in this project)
* pft_type: plant functional type extracted from MODIS (NOT USED in this project)
* pre1-12: Monthly Annual precipitation extracted from measurement year, from CRU ts 4.01 (mm/month) (NOT USED in this project)
* radi1-12: Monthly Shortwave solar radiation extracted from measurement year, from WFDEI (w/m2)
* tmn1-12: Monthly minimum temperature extracted from measurement year, from CRU ts 4.01 (degree celcius)
* tmx1-12: Monthly maximum temperature extracted from measurement year, from CRU ts 4.01 (degree celcius)
* vap1-12: Monthly vapor pressure extracted from measurement year, from CRU ts 4.01 (hPa) (NOT USED in this project)
* qair1-12: Monthly relative humidity from measurement year, from WFDEI (kg/kg)

#####The R code can be used to run the whole analysis for Peng et al 2021 Communications Biology.