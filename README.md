Welcome to the Data Sources used in the Data Center Impact Dashboard.

Original datasets, coming from various sources, were *cleaned* and *simplified* into the datasets above for faster loading in the Dashboard.

NOTE that these Data Sources do not include points data like data centers, fiber optic routes, power sources, etc -- such points are downloaded straight from the Dashboard!

NOTE that this documentation is being developed gradually, and may be incomplete for the time being. Please contact us at dashboard@rootedfutureslab.io with any questions.

# Energy

### Energy Reserve Margins
In **electric.pmtiles**, use `SUMMER_CAP` and `SUMMER_PEAK` to calculate the energy reserve margins, as in `(cap - peak) / peak`

# Water

### Aqueduct Water Risk
Use `bws_score` in **aqueduct4.pmtiles**

### Baseline Water Stress
Use `w_awr_def_tot_score` in **aqueduct4.pmtiles**

### Data Center Water Impact
Use `WSF_HUC4` in **siddik-wsf**

# Carbon

### Data Center Carbon Footprint
Use `CF_HUC4` in **subbasins.pmtiles**

# Network

### Underserved Networks
In **counties-network-poverty**, use `TotalBSLs` and `UnderservedBSLs` to calculate the ratio of underserved networks, as in `underserved / total`

# Demographics

### Poverty Ratio
Use `PCTPOVALL` in **counties-network-poverty.pmtiles**

### Tribal Lands
Use ***reservations.geojson*** -- this is incomplete -- adding the others soon
