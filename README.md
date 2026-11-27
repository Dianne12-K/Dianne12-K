<!--
  BANNER: replace with one of your own maps (a land-cover or NDVI map of Kakamega works well).
  Save it in this repo as banner.png, about 1280 x 400, then uncomment the line below.
-->
<!-- <p align="center"><img src="banner.png" alt="Land cover map of Kakamega County, Kenya" width="100%"></p> -->

# Hi, I'm Diana

**Geospatial data analyst and full-stack geospatial developer, based in Kenya.**

I currently work as a geospatial data analyst, where I build spatial models and turn spatial data into answers. I also design and build geospatial systems end to end: the map interface people use, the APIs and processing behind it, and the databases that hold the spatial data. Most of my work is for agriculture and health: mapping farms and monitoring crops, and working out how far people have to travel to reach care.

I'm also doing an MSc in Artificial Intelligence, and I'm using it to go deeper into machine learning on earth observation data and ecological niche modelling.

## What I work on

- **Full-stack geospatial development.**
  - Frontend: interactive web maps, drawing and editing tools, dashboards and charts.
  - Backend: REST APIs, authentication, and satellite and raster processing.
  - Databases: schema design, migrations, and storing and querying spatial data.
- **Spatial analysis.** Remote sensing, vegetation health (NDVI), land use and land cover, zonal statistics.
- **GeoAI.** Machine learning on satellite and spatial data, for classification, yield prediction and risk detection.
- **Spatial modelling.** Travel-time and accessibility modelling, ecological niche modelling, suitability and risk mapping.

## Projects

### [Smart Agriculture GIS Platform](https://github.com/Dianne12-K/smart-agriculture-farms)

A web GIS platform for farms in Kakamega County. Operators draw and manage farm boundaries on a map, then open satellite-derived analytics for any field: NDVI trends and stress hotspots, soil and land cover, yield prediction, crop recommendations, and flood, drought and fire risk.

Built with Vue 3, MapLibre GL, Terra Draw, Flask, PostgreSQL and Google Earth Engine.
[Live demo](https://smart-agriculture-farms.vercel.app) · [Backend repo](https://github.com/Dianne12-K/kakamega-backend-farmers)

<!-- Add a screenshot: <img src="https://raw.githubusercontent.com/Dianne12-K/smart-agriculture-farms/main/docs/screenshot.png" width="100%"> -->

### [GeoQuad Health Access](https://github.com/Dianne12-K/health-tracker-kenya)

Who in Kenya can reach a health facility, how long it takes them, and where a new facility would help most. It runs a national travel-time model on a 1 km grid, using raster cost-distance with Dijkstra's shortest path, the same approach as WHO's AccessMod. The inputs are the Kenya Master Health Facility List, WorldPop population and Malaria Atlas Project friction surfaces.

Planners can rank counties and constituencies by access, route from any point to the nearest facility, and place proposed facilities to see how many more people they bring within reach.

Built with Vue 3, MapLibre GL, Flask, NumPy and SciPy.
[Backend and model repo](https://github.com/Dianne12-K/health-tracker)

<!-- Add a screenshot of the Access Planner map here. -->

### [Land Use / Land Cover Analysis](https://github.com/Dianne12-K/land-use-land-cover)

A Python pipeline for land use and land cover mapping. It loads a study-area boundary, pulls ESA WorldCover data and clips it to the area of interest. Classification and change detection are in progress.

## Tools

- **Frontend:** Vue 3, Vite, Pinia, PrimeVue, Tailwind CSS, MapLibre GL, OpenLayers, Chart.js
- **Backend:** Python, Flask, REST APIs, JWT authentication, Google Earth Engine
- **Databases:** PostgreSQL, PostGIS, SQLite, SQLAlchemy
- **Desktop GIS:** QGIS
- **Data and modelling:** Python, NumPy, SciPy, machine learning, remote sensing

## Right now

- Working as a geospatial data analyst, focused on spatial modelling
- Studying for an MSc in Artificial Intelligence
- Adding cross-farm analytics and yield reporting to the Smart Agriculture platform
- Writing up more of my modelling work to share here

## Contact

[LinkedIn](https://www.linkedin.com/in/diana-khayenzeli-) · [Email](mailto:dianakhayenzeli111@gmail.com)
