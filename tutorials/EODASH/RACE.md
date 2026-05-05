# RACE DASHBOARD

The [Rapid Action for Citizens with Earth Observation Dashboard](https://race.esa.int/) (RACE) is a collaborative Earth Observation innovation initiative by [ESA](https://www.esa.int/) and the [European Commission - DG DEFIS](https://commission.europa.eu/about/departments-and-executive-agencies/defence-industry-and-space_en) with contributions from a wide network of European partners, focusing on Industry-developed indicators showcasing the breadth of European EO capabilities and their relevance to everyday life.


## Exploring the Dashboard
Based on accurate remote sensing observations, the Dashboard shows indicators covering different topics, such as pollution and environment, the economy, and society, derived from Earth Observations and other open data sources.
   
### Features
By clicking on the [Dashboard tab](https://race.esa.int/explore/?x=15.0000&y=48.0000&z=4.0000&template=expert) one can search by *Name* and for example by typing "turbidity", [Water Turbidity maps](https://race.esa.int/explore/?x=12.1420&y=44.9218&z=10.5781&template=expert&indicator=CNR_TUR_1&datetime=2022-09-10) can be explored. This indicator has been provided by [CNR-ISMAR](https://www.ismar.cnr.it/) as a result of the correlation of Sentinel-2A and 2B images with Po River discharge data from the [Environmental Protection Agency](https://www.arpae.it/it) and water levels from [AIPO](https://www.agenziapo.it/).<br>The dashboard provides the following <u>assets and features</u> to further examine the data:
* Light/Expert Mode
* Data Layers 
* Metadata (satellite, sensor, agency, temporal interval)
* Indicator description
* Date/BBOX selection and area computation on map
* External APIs execution
* Interactive timeseries chart generation
* Compare mode
* Extract storytelling configuration
* Provide Feedback 

### Indicators and Stories Interplay
*Storytelling* is another important capability characterizing the RACE Dashboard: it allows for the combination of interactive visual elements — such as maps and dynamic charts — with indicators to create narrative-driven guided tours.
<br>For example by flagging *Agriculture*  under the *Themes* bar and selecting [Crop Yield](https://race.esa.int/explore/?x=16.2850&y=49.8264&z=6.2521&template=expert&indicator=CROPOM_yield&datetime=2024-03-09), crop yield maps at regional level can be visualized. This indicator is provided as a service (integrating the *Crop Model API*) by [CropOM](https://cropom.com/) - a technology company (SME) that develops data integration platform services and integrated software for agriculture, insurance, and education. Moreover, by browsing the *Stories* section of the indicator properties, the corresponding [story](https://race.esa.int/story/?id=CropOM) can be accessed.

## RACE Resources
### EODASH Ecosystem 
The [eodash ecosystem](https://www.osgeo.org/projects/eodash/) is structured as an open community project (*OSGeo*) designed to be easily usable, configurable and extendable integrating multiple end-points and handling third-party APIs and services (for example [Sentinel Hub Statistical API](https://docs.sentinel-hub.com/api/latest/api/statistical/), [CropOM API](https://cropom.com/datacube)).<br> 
It is also present in the *Copernicus Data Space Ecosystem* (CDSE) as a [registered infrastructure](https://dataspace.copernicus.eu/ecosystem/services) providing services and tools for Earth observation data access and processing. It implements multiple standards, including:
* GeoJSON/FlatGeobuf
* GeoTIFF/COG
* WMS/WMTS
* STAC

Being STAC-compliant allows for the inspection of the RACE STAC Catalog content via the [STAC browser](https://radiantearth.github.io/stac-browser/#/external/ESA-eodashboards.github.io/RACE-catalog/RACE/catalog.json?.language=en). Moreover the static catalog can be accessed via the PySTAC library to explore the available collections, checking individual metadata fields, browsing through items ([EODashboard STAC access examples](https://eodashboard.org/notebook/?id=notebooks/eodashboard-stac-access/eodashboard-stac-access)). 
### EOxHub Workspace
[EOxHub Workspace](https://hub.eox.at/) implements the EODASH Ecosystem as a co-working platform, hosting different applications, allowing for the creation of end-to-end workflows, from private data generation to indicator visualization and narrative creation on the dashboard. 
<br>EOxHub Workspaces are based on the following applications ([Tutorial Workspace](https://workspace.eodashboardtutorial.hub-otc-sc.eox.at/)):
1) *JupyterHub*, a customizable datascience environment in which to select processing environment images and related resources
2) *Data Editor*, Git-based application allowing for data and metadata configuration
3) *Narrative Editor*, Git-based application supporting Markdown-based stories creation
4) *Conda Store*, to manage conda environment
<br>In particular the editors via the Workspace UI allow for creating and publishing on RACE Git repositories the configuration files for [indicators](https://github.com/ESA-eodashboards/RACE-catalog/tree/main/collections) and mark-down files for [descriptions](https://github.com/eurodatacube/eodash-assets/tree/main/collections) and [stories](https://github.com/ESA-eodashboards/RACE-narratives/tree/main).

The [EOxHub Workspaces documentation](https://documentation.hub.eox.at/) offers different sections where to discover additional details of the dashboard resources. In particular the *Tutorials* provide step-by-step procedures on the usage of the Data and Narrative Editors and how to [cross-link](https://documentation.hub.eox.at/editors-linking-stories-collections/) them.

## Network of Resources
Some RACE indicators are provided as a Service via the [NoR](https://nor-discover.org/) sponsorship, an ESA initiative to promote European cloud services for EO. 
 