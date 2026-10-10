## UAP Sightings and Nuclear Power Plant Proximity Analysis
### Project Overview
This project examines whether reported unidentified anomalous phenomena (UAP) sightings in the United States are associated with proximity to nuclear power plants. Using Python, I collected, cleaned, combined, and analyzed data from multiple sources to explore potential geographic relationships.
### Data Sources
- National UFO Reporting Center (NUFORC)
- U.S. nuclear power plant location data
- U.S. Census population data
- Geographic city and coordinate data
### Methods
- Web scraping and data collection
- Data cleaning and integration
- Geocoding and geographic distance calculations
- Exploratory data analysis and visualization
- Population-adjusted comparisons
### Key Finding
The analysis found a weak positive correlation (r = 0.1119) between sightings per 100,000 residents and distance to the nearest nuclear power plant. This does not establish a causal relationship.
### Tools
Python, pandas, NumPy, geopy, scikit-learn, and visualization libraries.
### Project Files
See the Jupyter notebooks in this repository for the analysis and methodology.
### Data Sources
National UFO Reporting Center (NUFORC) – UAP sighting reports collected through web scraping, including sighting dates, locations, and descriptions.
Global Power Plant Database – Nuclear power plant locations and geographic coordinates used to calculate distances from reported UAP sightings.
U.S. Census Bureau – County Population Estimates – County-level population estimates used to calculate sightings per 100,000 residents.
SimpleMaps – U.S. Cities Database – City and state information, including geographic coordinates, used to support location matching and data preparation.
Row Zero – County FIPS Data – County FIPS codes used to match geographic records across datasets.
### Data Availability
The original datasets are available through the links above. The notebooks are organized in the order of data collection, preparation, and analysis. Some datasets require downloading separately before running the notebooks.
### Limitations
UAP sightings are self-reported and may be affected by reporting bias, incomplete geographic information, and differences in population density. Although population-adjusted comparisons were used, other factors may influence the frequency and location of reported sightings. The results identify potential geographic relationships but do not establish causation.
