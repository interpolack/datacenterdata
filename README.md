Welcome to the Data Sources used in the Data Center Impact Dashboard.

Original datasets, coming from various sources, were *cleaned* and *simplified* into the datasets above for faster loading in the Dashboard.

NOTE that these Data Sources do not include points data like data centers, fiber optic routes, power sources, etc -- if something is represented already as a point or a line, such features are downloaded straight from the Dashboard!

# Energy

### Energy Reserve Margins
In **electric.pmtiles**, use `SUMMER_CAP` and `SUMMER_PEAK` to calculate the energy reserve margins, as in `(cap - peak) / peak`

# Water

### Aqueduct Water Risk
Use `bws_score` in **aqueduct4.pmtiles**

Or download the original, complete, and unsimplified data directly from https://www.wri.org/aqueduct/data

### Baseline Water Stress
Use `w_awr_def_tot_score` in **aqueduct4.pmtiles**

Or download the original, complete, and unsimplified data directly from https://www.wri.org/aqueduct/data

### Data Center Water Impact
Use `WSF_HUC4` in **siddik-wsf**

Or download the original, complete, and unsimplified data directly from https://iopscience.iop.org/article/10.1088/1748-9326/abfba1#erlabfba1s5

# Carbon

### Data Center Carbon Footprint
Use `CF_HUC4` in **subbasins.pmtiles**

Or download the original, complete, and unsimplified data directly from https://iopscience.iop.org/article/10.1088/1748-9326/abfba1#erlabfba1s5

# Network

### Underserved Networks
In **counties-network-poverty**, use `TotalBSLs` and `UnderservedBSLs` to calculate the ratio of underserved networks, as in `underserved / total`

Or download the original, complete, and unsimplified data directly from https://www.fcc.gov/BroadbandData

# Demographics

### Poverty Ratio
Use `PCTPOVALL` in **counties-network-poverty.pmtiles**

Or download the original, complete, and unsimplified data directly from https://www.census.gov/programs-surveys/saipe.html

### Tribal Lands
Use ***reservations.geojson*** -- this is incomplete -- adding the others soon

Or view the original data at https://www.honorearth.org/datacentertracker
