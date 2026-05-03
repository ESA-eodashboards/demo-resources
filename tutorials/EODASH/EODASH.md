# EARTH OBSERVING DASHBOARD

The [Earth Observing Dashboard](https://eodashboard.org/) is the result of a joint effort and cooperation between **ESA**, **NASA**, **JAXA** to bring and make available data, analytical and visualization tools to explore global events.
<br>It is grounded on the *Open Science* paradigm and based on Findability, Accessibility, Interoperability, and Reusability (FAIR) principles.
<br>Each Agency contributes with EO Data, scientific expertise and technology by means of:
* [EOxHub Workspaces](https://hub.eox.at/) - ESA
* [VEDA](https://www.earthdata.nasa.gov/dashboard/) - NASA
* [Earth-graphy](https://earth.jaxa.jp/en/) - JAXA

## Exploring the Dashboard
Based on accurate remote sensing observations, the Dashboard shows key indicators (such as maps and tabular timeseries data) to display water quality, climate change and health indicators, economic activities, etc. over different countries and regions around the world.
### Searching by Theme
By clicking on the [Dashboard tab](https://eodashboard.org/explore/?x=15.0000&y=48.0000&z=4.0000&template=expert) one can search by *Themes* and by selecting *Atmosphere* the corresponding indicators will be listed. <br>For example [Tropospheric NO2 concentrations maps](https://eodashboard.org/explore/?x=0.0000&y=0.0000&z=2.8642&datetime=2025-05-19&template=expert&indicator=N1_NO2) from **ESA's Sentinel-5P** (Copernicus Programme) mission are used for monitoring air quality and the dashboard provides the following <u>assets and features</u> to further examine the data:
* Light/Expert Mode
* Data Layers 
* Metadata (satellite, sensor, agency, temporal interval)
* Indicator description
* Date/BBOX selection and area computation on map
* Interactive timeseries chart generation
* Compare mode
* Extract storytelling configuration
* Provide Feedback
   
### Searching by Name
By clicking on the [Dashboard tab](https://eodashboard.org/explore/?x=15.0000&y=48.0000&z=4.0000&template=expert) one can search by *Name* and for example by typing "chlorophyll", [Chlorophyll-a concentration from GCOM-C](https://eodashboard.org/explore/?indicator=N3a2_chl_jaxa&x=12.9000&y=45.1537&z=8.9359&datetime=2026-02-21&template=expert&poi=NorthAdriatic) (**JAXA**) can be explored. 

### Indicators and Stories Interplay
*Storytelling* is another important capability characterizing the Earth Observing Dashboard: it allows for the combination of interactive visual elements — such as maps and dynamic charts — with indicators to create narrative-driven guided tours.
<br>For example by typing "nightlights" in the Indicators Search bar and selecting [Night Lights in Rural Areas](https://eodashboard.org/explore/?x=-87.5000&y=41.8288&z=5.8958&template=expert&indicator=NTLR&datetime=2019-01-01), the nighttime light maps obtained by post-processing and color blending imageries produced by the Suomi NPP (a joint mission of NOAA and **NASA**) can be visualized together with the related [Jupyter Notebook](https://eodashboard.org/notebook/?id=notebooks/nightlights-notebook/night-lights-blending) (for results reproducibility) and the corresponding [story](https://eodashboard.org/story/?id=nightlights_from_space).

## EO Dashboard Resources
### EODASH Ecosystem 
The [eodash ecosystem](https://www.osgeo.org/projects/eodash/) is structured as an open community project (OSGeo), designed to be:
* easily usable
* configurable
* extendable
<br>It is also present in the **Copernicus Data Space Ecosystem** (CDSE) as a [registered infrastructure](https://dataspace.copernicus.eu/ecosystem/services) providing services and tools for Earth observation data access and processing.
<br>
It implements the following standards:
* GeoJSON
* COG
* STAC (browse the EODASH catalog )
* WMS/WMTS
Being STAC-compliant allows also for the inspecting of the entire EODASH catalog via the [STAC-browser](https://radiantearth.github.io/stac-browser/#/external/esa-eodashboards.github.io/eodashboard-catalog/trilateral/catalog.json?.language=en).
### EOxHub Workspace
[EOxHub Workspace](https://hub.eox.at/) implements the EODASH Ecosystem as a co-working platform, hosting different applications, allowing for the creation of end-to-end workflows, from private data generation to indicator visualization and narrative creation on the dashboard. 
<br>EOxHub Workspaces are based on the following applications:
1) JupyterLab, for the selection of processing environment images and related resources
2) Data Editor
3) Narrative Editor
4) Conda Store, to manage conda environment

## Further Information
The [EOxHub Workspaces documentation](https://documentation.hub.eox.at/) offers different sections where to discover additional details of the dashboard resources. In particular the *Tutorials* provide step-by-step procedures on the usage of the Data and Narrative Editors and how to [cross-link](https://documentation.hub.eox.at/editors-linking-stories-collections/) them.
