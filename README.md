# ECCC 2016 Snow on Sea Ice Campaign
## Synopsis

The ECCC 2016 snow on sea ice campaign took place near Eureka, Nunavut, Canada on landfast ice (80.0°N 85.9°W). Snow property measurements were collected over a 9-day period between 8 April 2016 and 17 April 2016 within Eureka Sound and Slidre Fjord. Sea ice near Eureka was principally landfast first year ice (FYI) with embedded floes of multi-year ice (MYI) imported from the Arctic Ocean via Nansen Sound. FYI near Eureka formed as large level pans with limited deformation. Imported MYI was heavily hummocked from exposure to previous melt. Measurements at Eureka were grouped by sites  (250 x 100 m) with similar surface conditions. A total of 8 sites were completed with 6 on FYI and 2 on MYI. This dataset contains snow depth measurements were completed with [GPS-enabled Snow Hydro Magnaprobe](http://www.snowhydro.com/products/column2.html) units, snow density and water equivalent measurements completed with an ESC-30 corer, and manual ice auger measurements of thickness and freeboard.

 Measurements were coordinated with [NASA’s Operation IceBridge](https://www.nasa.gov/mission_pages/icebridge/index.html) overlfights on 19 April 2016 ([see mission report for details](https://espo.nasa.gov/oib/flight_reports/Other_NOAA_P-3_04_19_16))

## Format
**Snow thickness measurements on sea ice are provided as a single comma delimited file with 7 columns:**

*timestamp*: Time of collection in format yyyy-mm-dd hh:mm:ss GMT+5

*lat* and *lon*: Latitude and longitude in decimal degrees with WGS84 as the CRS. All measurements are on fast ice and do not require drift adjustment.

*depth*: Snow depth in cm. Calibration steps were taken to adjust for small (mm scale) errors unique to each unit. Raw datasets are available upon request.

*site*: Identifies the site by a unique name used in the Eureka 2016 planning.

*ice_type*: Ice type noted at first or multi-year


**Snow density and water equivalent measurements on sea ice are provided as a single comma delimited file with 10 columns:**

*depth_x*: Snow depth in cm. Note that measurements are taken in pairs at each location noted with a or b.

*density_x*: Bulk snow density in kg m<sup>-3</sup>

*swe_x*: Snow water equivalent in mm

*lat* and *lon*: Latitude and longitude in decimal degrees with WGS84 as the CRS. All measurements are on fast ice and do not require drift adjustment.

*site*: Identifies the site by a unique name used in the Eureka 2016 planning.

*ice_type*: Ice type noted at first or multi-year

**Ice thickness and freeboard measurements are provided as a single comma delimited file  file with 7 columns:**

*ice_thickness*: Ice thickness in cm

*freeeboard*: Ice freeboard in cm

*snow_depth*: Snow depth in cm

*lat* and *lon*: Latitude and longitude in decimal degrees with WGS84 as the CRS. All measurements are on fast ice and do not require drift adjustment.

*site*: Identifies the site by a unique name used in the Eureka 2016 planning.

*ice_type*: Ice type noted at first or multi-year

## Contact
Josh King, Research Scientist, joshua.king[at]canada.ca

## License
This dataset is licensed under the [Open Government License of Canada](http://open.canada.ca/en/open-government-licence-canada)
and is subject to the [Copyright Act of Canada](http://laws-lois.justice.gc.ca/eng/acts/C-42/index.html). Additional information can be found at the [Government of Canada's Open Government portal](http://open.canada.ca)
