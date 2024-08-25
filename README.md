# Data Scientist/Analyst

#### Technical Skills: R, Python, SQL, Google Earth Engine (Javascript), Google Cloud Platform, Google BigQuery, Arcpy, ArcGIS, QGIS

## Education
- Ph.D., Toxicology & Environmental Health  | Utrecht University | _Sept 2020-Present_
- M.S., Earth Sciences	| Utrecht University | _Sept 2018-Jul 2020_
- B.S., Environmental & Agriculture Engineering | National Taiwan University | _Sept 2014-Jun 2018_

## Work Experience
**Data Scientist/Analyst (Road traffic) @ Utrecht University (_Mar 2023  - Present_)**
EU-funded project—road traffic noise modelling
- Analyze and visualize geospatial large data to uncover key insights using PostgreSQL and R, resulting in a 4% increase in road traffic modelling, contributing to urban environmental sustainability and decision-making for 5+ EU institutions
- Collaborate with 14 researchers from cross-functional teams, ranging from epidemiologists, model developers, software engineers, stakeholders, and statisticians



**Data Scientist/Analyst (Air quality) @ Utrecht University (_December 2020 - Present_)**
-	Publish 3 peer-reviewed papers as first author with 36 citations, creating societal impact through developing data dashboards for visualizing [annual](https://youchenshenuu.users.earthengine.app/view/expanse-air-pollution-20-yr-maps) and [monthly](https://youchenshenuu.users.earthengine.app/view/expanse-monthly-average-air-pollution-maps) geospatial maps – data featured in [Guardian news](https://www.theguardian.com/environment/2023/sep/20/revealed-almost-everyone-in-europe-breathing-toxic-air)
-	Collaborate with 12 cross-functional researchers, ranging from software developer, 
-	Wrangled and processed 1 TB Waze traffic jam data using BigQuery on Google Cloud Platform and created visualization with Looker Studio to make data-driven decisions with stakeholders
-	Develop an anomaly detection algorithm that identifies outliers in time-series data with 75%+ validity for modelling purposes
-	Enhance prediction accuracy by 19% in air quality models, providing actionable insights for stakeholders to promote a sustainable environment
-	Present data visualization results to stakeholders at EU institutions to make actionable plans of effectively understanding health impacts of air quality and increasing public awareness through 5+ research projects, 2+ infographics, 10+ charts and 2+ data dashboards
-	Create an automated data pipeline for web data scraping and processing via Python and R, reducing processing time of geospatial and remote sensing data by five-fold using cloud computation infrastructure (Google Earth Engine and Google Cloud Platform), allowing faster analysis and decision-making
-	Share data insights with colleagues, resulting in 4 peer-reviewed papers (and 3 other papers in preparation)

**Research Assistant @ Utrecht University (_Dec 2018 — Jun 2019_)**
-	Quantified and analyzed dynamics in mangrove in Suriname to develop sustainable coastal protection methods and to enhance biodiversity, communicating results in a peer-reviewed paper

## Projects
### Europe-wide air quality modelling from 2000 to 2019 at a 25mx25m resolution
[Publication - Annual](https://www.sciencedirect.com/science/article/pii/S0160412022004123)

[Publication - Monthly](https://www.sciencedirect.com/science/article/pii/S0048969724006879)

[Github Repo - Annual](https://github.com/co822ee/EXPANSE_algorithm)

[Github Repo - Monthly](https://github.com/co822ee/expanse_multiyear/)

[Visualization dashboard - Annual](https://youchenshenuu.users.earthengine.app/view/expanse-air-pollution-20-yr-maps)

[Visualization dashboard - Monthly](https://youchenshenuu.users.earthengine.app/view/expanse-monthly-average-air-pollution-maps)

Used **R & Google Earth Engine (Javascript)** to train three machine learning algorithms were used (**Random Forests**, **Geographically Weighted Regression**, **Supervised Linear Regression**) which estimated particulate matter, nitrogen dioxide, and ozone concentrations based on over 250 geospatial variables and 20k monitoring observations across Europe over 20 years. We found that using spatially-varying linear regression model structures would give high predictive accuracy than nonlinear regression and spatially-fixed linear regression. The resulting air quality maps allow us to disentangle key interactions between the environment and human health.

![Air quality maps](/assets/img/air-quality-maps.jpg)

### Europe-wide high-spatial resolution air pollution models are improved by including traffic flow estimates on all roads

[Publication](https://www.sciencedirect.com/science/article/pii/S1352231024003947)

[Github Repo](https://github.com/co822ee/eu_roadTraffic)

Used **R & Google Earth Engine (Javascript)** to develop **Random Forests** which estimated road traffic flow based on over 250 geospatial variables. We found regression variables can be used to accurately estimate on-road vehicle numbers at large spatial scales with high accuracy (r2 > 0.7) and that smaller particles are better estimated than larger ones. Inferring environmental conditions solely from biometric measurements allows us to disentangle key interactions between the environment and the body.

![Bike Study](/assets/img/AtmosphericEnvironment-toc.jpg)

### Europe-wide road traffic noise modelling

Used **R & PostgreSQL** to estimate road traffic noise using a physically-based noise model (CNOSSOS-EU) at millions of points across Europe. I created an automated data pipeline for parallel computing on Dutch national supercomputer (Snellius) on Linux.

![Noise map](/assets/img/noise-utrecht.jpg)

_Noise level estimates in the city center of Utrecht_


## Publications
1. Shen, Y., de Hoogh, K., Schmitz, O., Clinton, N., Tuxen-Bettman, K., Brandt, J., Christensen, J.H., Frohn, L.M., Geels, C., Karssenberg, D., Vermeulen, R., Hoek, G., 2022a. Europe-wide air pollution modeling from 2000 to 2019 using geographically weighted regression. Environ. Int. 168, 107485. [https://doi.org/10.1016/j.envint.2022.107485](https://doi.org/10.1016/j.envint.2022.107485)
2. Shen, Y., de Hoogh, K., Schmitz, O., Gulliver, J., Vienneau, D., Vermeulen, R., Hoek, G., Karssenberg, D., 2024b. Europe-wide high-spatial resolution air pollution models are improved by including traffic flow estimates on all roads. Atmos. Environ. 335, 120719. [https://doi.org/10.1016/J.ATMOSENV.2024.120719](https://doi.org/10.1016/J.ATMOSENV.2024.120719)
3. Shen, Y., Ruijsch, J., Lu, M., Sutanudjaja, E.H., Karssenberg, D., 2022b. Random forests-based error-correction of streamflow from a large-scale hydrological model: Using model state variables to estimate error terms. Comput. Geosci. 159, 105019. [https://doi.org/10.1016/j.cageo.2021.105019](https://doi.org/10.1016/j.cageo.2021.105019)
4. Ndiaye, A., Shen, Y., Kyriakou, K., Karssenberg, D., Schmitz, O., Flückiger, B., Hoogh, K. de, Hoek, G., 2024. Hourly land-use regression modeling for NO2 and PM2.5 in the Netherlands. Environ. Res. 256, 119233. [https://doi.org/10.1016/J.ENVRES.2024.119233](https://doi.org/10.1016/J.ENVRES.2024.119233)
5. Yuan, Z., Kerckhoffs, J., Shen, Y., de Hoogh, K., Hoek, G., Vermeulen, R., 2023. Integrating large-scale stationary and local mobile measurements to estimate hyperlocal long-term air pollution using transfer learning methods. Environ. Res. 228. [https://doi.org/10.1016/J.ENVRES.2023.115836](https://doi.org/10.1016/J.ENVRES.2023.115836)
6. de Jong, S.M., Shen, Y., de Vries, J., Bijnaar, G., van Maanen, B., Augustinus, P., Verweij, P., 2021. Mapping mangrove dynamics and colonization patterns at the Suriname coast using historic satellite data and the LandTrendr algorithm. Int. J. Appl. Earth Obs. Geoinf. 97, 102293. [https://doi.org/10.1016/j.jag.2020.102293](https://doi.org/10.1016/j.jag.2020.102293)
7. Magni, M., Sutanudjaja, E.H., Shen, Y., Karssenberg, D., 2023. Global streamflow modelling using process-informed machine learning. J. Hydroinformatics 25, 1648–1666. [https://doi.org/10.2166/HYDRO.2023.217](https://doi.org/10.2166/HYDRO.2023.217)


