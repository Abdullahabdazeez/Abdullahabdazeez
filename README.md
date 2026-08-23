<p align="center">
  <img src="assets/github-profile-banner.png" alt="Abdullah Abdazeez Ayomide — Geospatial Planner and GIS & Remote Sensing Analyst" width="100%">
</p>

<h1 align="center">Abdullah Abdazeez Ayomide</h1>

<p align="center">
  <strong>Geospatial Planner · GIS & Remote Sensing Analyst · Urban and Environmental Planning Researcher</strong>
</p>

<p align="center">
  <a href="https://ng.linkedin.com/in/abdazeez-abdullah-4b814719a">LinkedIn</a> ·
  <a href="mailto:abdazeezabdullah1@gmail.com">Email</a> ·
  Nigeria
</p>

## About me

I am an Urban and Regional Planning graduate from the Federal University of Technology, Akure. I use GIS, Earth observation and spatial modelling to examine urban growth, service accessibility, environmental change and climate-related planning problems.

My work sits between spatial analysis and practical planning: I am interested in evidence that can support decisions, not maps without interpretation.

**Research direction:** geospatial decision support for sustainable, resilient and equitable urban and environmental planning.

## Public portfolio

Five applied project repositories are currently public and accessible directly from this profile. Additional projects remain private while their final publication packages are being prepared.

| Theme | Public project | What it shows | Status |
|---|---|---|---|
| Land-cover change | [Ibadan land-cover change, 2013–2023](https://github.com/Abdullahabdazeez/ibadan-lulc-change) | Built-up land increased from **99.866 km² to 330.177 km²**; **246.104 km²** converted from vegetation to built-up. Final locked-holdout OA: **87.50%**. | **Validated · final** |
| Healthcare accessibility | [Kano primary-healthcare accessibility](https://github.com/Abdullahabdazeez/kano-primary-healthcare-accessibility) | Network travel time and 15-minute 2SFCA analysis across **1,584 PHCs, 484 wards and 16,789 demand cells**. The +20 PHC scenario improved statewide modelled accessibility by **1.26%**. | **Validated · final** |
| Transport accessibility | [Lagos formal public-transport accessibility](https://github.com/Abdullahabdazeez/lagos-public-transport-accessibility) | **53.44%** of the analysed population was within 30 minutes of mapped formal/core transit; **46.56%** was outside that threshold or in a structural network gap. | **Validated · final** |
| Coastal adaptation | [Ayetoro 3D coastal vulnerability](https://github.com/Abdullahabdazeez/ayetoro-3d-coastal-vulnerability) | Assessed **1,628 buildings**; **72.17%** were High or Very High relative vulnerability. The 3D component is explicitly separated from the vulnerability model. | **Validated · final** |
| Urban growth modelling | [Abuja CA–Markov urban-growth model](https://github.com/Abdullahabdazeez/abuja-urban-growth-ca-markov) | Original CA–Markov scenario retained for provenance while the historical LULC inputs, transition logic and validation framework are being rebuilt. | **Public · reconstruction in progress** |

> Public repositories contain the project-facing documentation and selected outputs. Large reconstruction archives and intermediate technical files are kept separately where appropriate.

## Featured work

### 1. Ibadan land-cover change, 2013–2023

**Question:** How did Ibadan's land-cover pattern change over a decade, and what land cover supplied most new urban development?

A forensic audit exposed weaknesses in the original validation evidence, so the earlier headline results were withdrawn and the classification was rebuilt. The final reconstruction uses seasonally matched Landsat predictors, blinded human review, leakage controls, a locked independent holdout and wall-to-wall consistency checks.

**Final result:** built-up land increased by **230.311 km²**, and **99.14% of gross new built-up land** came from areas mapped as vegetation in 2013.

[View validated repository →](https://github.com/Abdullahabdazeez/ibadan-lulc-change)

### 2. Kano primary-healthcare accessibility

**Question:** Where are the main spatial gaps in primary healthcare access across Kano State, and how much can carefully selected new PHC locations improve access?

The project combines network travel time, population demand and a 15-minute two-step floating catchment area analysis. It also tests alternative PHC expansion scenarios and distance-decay assumptions.

**Planning result:** targeted facilities improve access in selected communities, but even the +20 PHC scenario changes the statewide population-weighted accessibility score by only **1.26%**.

[View validated repository →](https://github.com/Abdullahabdazeez/kano-primary-healthcare-accessibility)

### 3. Lagos formal public-transport accessibility

**Question:** How easily can residents reach Lagos's mapped formal/core public-transport network on foot?

The study combines a pedestrian network, WorldPop population data and 219 mapped formal/core transit access points. It separates time-based accessibility gaps from structural network gaps and states clearly that informal transport is not comprehensively represented.

[View validated repository →](https://github.com/Abdullahabdazeez/lagos-public-transport-accessibility)

### 4. Ayetoro coastal vulnerability

**Question:** Where are buildings in Ayetoro most vulnerable to coastal hazards, and how can geospatial analysis support adaptation planning?

The final model combines shoreline proximity, low elevation, settlement density, road density and facility exposure. Historical evidence is used for validation rather than model construction, and estimated building heights are used only for 3D visualisation.

[View validated repository →](https://github.com/Abdullahabdazeez/ayetoro-3d-coastal-vulnerability)

## Projects currently being strengthened

### Abuja urban-growth CA–Markov

The original 2035 scenario remains public for transparency, but the project is now undergoing a controlled reconstruction. The current priority is to repair the historical 2005/2015/2025 LULC inputs, resolve implausible transition behaviour, strengthen suitability discrimination and replace Kappa-led land-change validation with more interpretable change diagnostics such as Figure of Merit and quantity/allocation disagreement.

Until that reconstruction is complete, the existing 2035 scenario should be treated as **provisional**, not as a final forecast.

[View reconstruction repository →](https://github.com/Abdullahabdazeez/abuja-urban-growth-ca-markov)

## Additional portfolio work

The wider portfolio also includes ongoing or publication-preparation work in:

- Northern Nigeria drought and vegetation stress;
- Enugu land-suitability modelling;
- Borno conflict and displacement analysis;
- Lokoja flood hazard and vulnerability; and
- Tartu urban green-infrastructure ecosystem-service deficit.

These repositories remain private until their final checks are complete.

## What I bring to a project

- **Planning perspective:** I connect spatial results to land-use decisions, service access, environmental management and community needs.
- **Scientific caution:** I distinguish association from causation, scenarios from forecasts, susceptibility from hydraulic risk, and modelled access from actual service quality.
- **Reproducible work:** I document data sources, methods, validation evidence, limitations and reusable outputs.
- **Clear communication:** I write for both technical and non-technical readers and combine maps, charts and concise interpretation.
- **Willingness to correct:** when an audit exposes a weakness, I document it and rebuild the analysis rather than preserve an unsupported result.

## Technical toolkit

| Area | Tools and methods |
|---|---|
| GIS and cartography | QGIS, ArcGIS/ArcMap, Google Earth Engine |
| Python and spatial data | Python, GeoPandas, Rasterio, Pandas, NumPy, scikit-learn, OSMnx, NetworkX |
| Remote sensing | Landsat, Sentinel-2, MODIS, Dynamic World, VIIRS, CHIRPS |
| Spatial analysis | LULC classification, change detection, network analysis, 2SFCA, CA–Markov, AHP/MCDA, vulnerability and suitability modelling |
| Research workflow | WorldPop, OpenStreetMap, Google Colab, Git, GitHub, SPSS, Zotero |
| Communication | Technical reports, project boards, publication maps, charts and planning-focused interpretation |

## Academic and practical background

- **B.Tech, Urban and Regional Planning** — Federal University of Technology, Akure
- **Environmental Planning Intern, Gbolabs Environmental Agency** — land-use analysis, environmental assessment, neighbourhood planning and GIS-supported site studies
- **Former planning intern, Ondo State Ministry of Physical Planning and Urban Development**
- Trained university IT students in practical GIS and spatial-data applications
- Participated in community sensitisation for a proposed Ondo State flyover, engaging residents and corridor users on its transport and traffic purpose

## Current interests

I am open to:

- master's and research opportunities in geospatial planning, remote sensing, climate adaptation and urban resilience;
- entry-level GIS, remote-sensing and environmental-planning roles;
- research collaboration involving spatial decision support; and
- projects that connect technical analysis with real planning problems.

## Contact

- **LinkedIn:** [Abdazeez Abdullah](https://ng.linkedin.com/in/abdazeez-abdullah-4b814719a)
- **Email:** [abdazeezabdullah1@gmail.com](mailto:abdazeezabdullah1@gmail.com)
- **GitHub:** [github.com/Abdullahabdazeez](https://github.com/Abdullahabdazeez)
- **Location:** Nigeria

---

<p align="center"><strong>Planning better places with geospatial data.</strong></p>
