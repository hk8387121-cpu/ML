# Master Dataset Catalog — All 33 ML Features

> Repeated datasets are intentionally listed under multiple features when they are useful for multiple models.

## #2 AI Crop Planning

### Dataset 1 — FAOSTAT Crop and Livestock Products
- Link: https://www.fao.org/faostat/en/#data/QCL
- Type: Global agricultural production time series
- Modalities: Tabular
- Use: Historical crop production, area harvested, yield and production trends for crop planning.
- Status: Real public data; verify current download/API terms.

### Dataset 2 — Crop Recommendation Dataset
- Link: https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
- Type: Soil + climate crop recommendation
- Modalities: Tabular
- Typical fields: N, P, K, temperature, humidity, pH, rainfall, recommended crop.
- Use: Direct baseline for recommendation classification.

### Dataset 3 — NASA POWER Agroclimatology
- Link: https://power.larc.nasa.gov/
- Type: Weather and agroclimatology
- Modalities: Time series
- Use: Temperature, precipitation, radiation and related inputs for location-aware planning.

## #3 Smart Irrigation

### Dataset 1 — Crop Water Requirement and Irrigation Water Demand, Yellow River Basin
- Link: https://zenodo.org/records/18628324
- Type: 500 m annual CWR/IWD for 25 crops, 2000–2020
- Modalities: Raster/geospatial
- Use: Direct target/reference data for irrigation demand models.

### Dataset 2 — ERA5-Land
- Link: https://cds.climate.copernicus.eu/datasets/reanalysis-era5-land
- Type: Global land reanalysis
- Modalities: Gridded time series
- Use: Weather and land-surface variables for ET0 and water-demand estimation.

### Dataset 3 — NASA POWER
- Link: https://power.larc.nasa.gov/
- Type: Location-based meteorology
- Use: Temperature, humidity, solar radiation and precipitation inputs for ET-based irrigation.

## #4 Crop Health AI

### Dataset 1 — PlantVillage
- Link: https://github.com/spMohanty/PlantVillage-Dataset
- Type: Crop leaf disease classification
- Modalities: Images + labels
- Size: 54,306 images; 14 crops; 26 disease/healthy classes (as described by the dataset project).
- License: CC BY 4.0 is reported by the dataset source.
- Use: Primary CNN training dataset.

### Dataset 2 — New Plant Diseases Dataset
- Link: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
- Type: Healthy/diseased crop leaf images
- Size: About 87K RGB images across 38 classes.
- Use: Larger classification training/validation pool.

### Dataset 3 — PlantDoc
- Link: https://github.com/pratikkayal/PlantDoc-Dataset
- Type: In-the-wild plant disease dataset
- Modalities: Images + object/class annotations
- Use: More realistic field conditions than controlled-background datasets.

## #9 Harvest & Market

### Dataset 1 — India Government Open Data / Mandi Price Data
- Link: https://www.data.gov.in/
- Type: Agricultural market prices and commodity data
- Modalities: Tabular/API
- Use: Harvest timing, sale-price estimation and market matching.

### Dataset 2 — AGMARKNET
- Link: https://agmarknet.gov.in/
- Type: Indian agricultural market prices
- Modalities: Tabular/web data
- Use: Market-level arrivals and modal prices.

### Dataset 3 — FAOSTAT Prices and Trade
- Link: https://www.fao.org/faostat/en/
- Type: Global food/agricultural data
- Use: International context and cross-market features.

## #11 Satellite Crop Stress Prediction

### Dataset 1 — Sentinel-2 via Copernicus Data Space
- Link: https://dataspace.copernicus.eu/
- Type: Multispectral Earth observation
- Modalities: Raster time series
- Use: NDVI/NDRE and vegetation-stress feature extraction.

### Dataset 2 — Landsat Collection 2
- Link: https://www.usgs.gov/landsat-missions/landsat-collection-2
- Type: Multispectral satellite imagery
- Modalities: Raster time series
- Use: Long-term crop/vegetation stress monitoring.

### Dataset 3 — USDA CropScape / Cropland Data Layer
- Link: https://nassgeodata.gmu.edu/CropScape/
- Type: Annual crop-type maps
- Modalities: Geospatial raster
- Use: Crop mask and field/crop context when combined with satellite imagery.

## #12 Drone/Video Plant Counting

### Dataset 1 — UAV Rice Plant Counting / OPIA
- Link: https://ngdc.cncb.ac.cn/opia/dataset/datasets?dataId=4
- Type: UAV rice plant counting
- Size: 109 JPEG images; about 415 MB; average resolution 1368×912.
- Geography: Nanchang, Jiangxi, China
- Modalities: RGB UAV images + annotations
- Use: Direct object-counting benchmark.

### Dataset 2 — Rice Plant Counting Dataset (research repositories)
- Link: https://www.kaggle.com/search?q=rice+plant+counting
- Type: Rice/UAV/plant-counting datasets
- Use: Supplemental detector training.
- Note: Kaggle search is a discovery page; verify individual dataset licensing before use.

### Dataset 3 — Weizmann / Generic Counting Benchmarks
- Link: https://www.crowdcounting.org/
- Type: Generic visual counting benchmarks
- Use: Architecture/debugging for density/counting methods; not agriculture-specific.

## #13 Weed Species Classification

### Dataset 1 — Weed25
- Link: https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2022.1053329/full
- Type: Field weed image dataset
- Size: 14,023 images in 25 categories.
- Use: Primary weed classification/detection dataset.

### Dataset 2 — DeepWeeds
- Link: https://github.com/AlexOlsen/DeepWeeds
- Type: Weed species recognition
- Modalities: Images + labels
- Use: Field-oriented weed classification.

### Dataset 3 — Kaggle Weed Datasets Search
- Link: https://www.kaggle.com/search?q=weed+classification
- Type: Collection of weed image datasets
- Use: Additional species/background variation.
- Note: Verify exact dataset page and license before use.

## #14 Grain Quality Scoring

### Dataset 1 — GrainSet
- Link: https://github.com/hellodfan/GrainSet
- Type: Annotated cereal grain kernel image database
- Size/coverage: Wheat ~200K, Maize ~19K, Sorghum ~102K, Rice ~31K; plus smaller/raw variants.
- Use: Kernel classification, segmentation and visual quality inspection.

### Dataset 2 — GrainSet Wheat
- Link: https://doi.org/10.6084/m9.figshare.22992317.v2
- Type: Wheat kernel images + masks/annotations
- Use: Defect/quality visual model.

### Dataset 3 — GrainSet Rice
- Link: https://doi.org/10.6084/m9.figshare.22987292.v3
- Type: Rice kernel images
- Use: Rice quality and morphology models.

## #15 Hyperlocal Mandi Price Forecasting

### Dataset 1 — AGMARKNET
- Link: https://agmarknet.gov.in/
- Use: Market-level time series for Indian mandis.

### Dataset 2 — data.gov.in agricultural market datasets
- Link: https://www.data.gov.in/
- Use: Government open data/API sources for commodity prices, arrivals and market characteristics.

### Dataset 3 — FAOSTAT
- Link: https://www.fao.org/faostat/en/
- Use: Long-run commodity-price context and external regressors.

## #16 Yield Forecasting with Uncertainty

### Dataset 1 — CYCleSS
- Link: https://springernature.figshare.com/articles/dataset/CYCleSS_the_Crop_Yields_Climate_Soils_and_Satellites_Dataset/27225807
- Type: Crop yields + weather + soil + satellite-derived data
- Coverage: 934 fields across England.
- Use: Multimodal yield prediction and uncertainty modelling.

### Dataset 2 — FAOSTAT Crop and Livestock Products
- Link: https://www.fao.org/faostat/en/#data/QCL
- Use: Global historical yield baselines.

### Dataset 3 — USDA NASS Quick Stats
- Link: https://quickstats.nass.usda.gov/
- Type: Official US agricultural statistics
- Modalities: Tabular/time series
- Use: Crop yield forecasting and regional covariates.

## #17 Water Demand Forecasting

### Dataset 1 — Yellow River Basin Irrigation Demand
- Link: https://zenodo.org/records/18628324
- Type: 500 m CWR/IWD for 25 crop types, 2000–2020
- Use: Direct target data for crop-water forecasting.

### Dataset 2 — ERA5-Land
- Link: https://cds.climate.copernicus.eu/datasets/reanalysis-era5-land
- Use: Weather/soil forcing.

### Dataset 3 — NASA GLDAS
- Link: https://disc.gsfc.nasa.gov/datasets?project=GLDAS
- Type: Land-surface and hydrological reanalysis
- Use: Soil moisture, evapotranspiration and surface energy predictors.

## #18 Soil Health Modeling

### Dataset 1 — SoilHealthDB
- Link: https://agdatacommons.nal.usda.gov/articles/dataset/Data_from_A_database_for_global_soil_health_assessment/24853500
- Type: Global soil-health field database
- Size: 5,907 rows × 268 columns; 354 sites in 42 countries are described by the source.
- Use: Soil-health indicators and management-effect modelling.

### Dataset 2 — SoilGrids
- Link: https://soilgrids.org/
- Type: Global gridded soil properties
- Modalities: Raster
- Use: Spatial soil-property prediction and field-level features.

### Dataset 3 — ISRIC World Soil Database
- Link: https://www.isric.org/explore/wossis
- Type: Global soil observations/resources
- Use: Soil-property enrichment and spatial validation.

## #19 Variety Recommendation Engine

### Dataset 1 — CGIAR / CIMMYT wheat data resources
- Link: https://www.cimmyt.org/
- Type: Crop breeding and trial resources
- Use: Variety × environment × yield relationships.

### Dataset 2 — Genesys PGR
- Link: https://www.genesys-pgr.org/
- Type: Plant genetic resources metadata
- Use: Variety/accession characteristics for recommendation features.

### Dataset 3 — USDA NASS Crop Data
- Link: https://quickstats.nass.usda.gov/
- Use: Regional crop performance/context for variety matching when variety-level labels are available from companion trial datasets.

## #20 Pest Outbreak Spread Prediction

### Dataset 1 — FAO Locust Watch
- Link: https://www.fao.org/locust-watch/
- Type: Desert locust monitoring
- Use: Outbreak/spread history and environmental context.

### Dataset 2 — NASA Earthdata
- Link: https://www.earthdata.nasa.gov/
- Type: Earth-observation and climate data
- Use: Vegetation, rainfall, land-surface predictors for outbreak modelling.

### Dataset 3 — FAOSTAT Plant Protection / Crop Data
- Link: https://www.fao.org/faostat/en/
- Use: Crop context and country-level agricultural variables.

## #21 Voice-First AI Assistant

### Dataset 1 — Mozilla Common Voice
- Link: https://commonvoice.mozilla.org/en/datasets
- Type: Multilingual speech + transcripts
- Use: ASR training/evaluation, including Indian-language resources where available.

### Dataset 2 — OpenSLR
- Link: https://www.openslr.org/
- Type: Speech corpora
- Use: Additional multilingual ASR datasets.

### Dataset 3 — AI4Bharat Indic speech resources
- Link: https://ai4bharat.iitm.ac.in/
- Type: Indian-language speech/NLP datasets and models
- Use: Indian-language voice assistant adaptation.

## #22 Multimodal Query Understanding

### Dataset 1 — MS COCO
- Link: https://cocodataset.org/
- Type: Image + captions/object annotations
- Use: General image-text representation learning.

### Dataset 2 — VQA v2
- Link: https://visualqa.org/
- Type: Visual question answering
- Use: Image + question + answer supervision.

### Dataset 3 — GQA
- Link: https://cs.stanford.edu/people/dorarad/gqa/
- Type: Compositional visual QA
- Use: More challenging multimodal reasoning.

## #23 RL Crop Rotation Planner

### Dataset 1 — AgMIP
- Link: https://agmip.org/
- Type: Agricultural model intercomparison data/resources
- Use: Crop/climate scenario generation and reward simulation.

### Dataset 2 — DSSAT
- Link: https://dssat.net/
- Type: Crop growth simulation platform/data resources
- Use: Generate rotation scenarios, yields and resource responses for RL environments.

### Dataset 3 — APSIM
- Link: https://www.apsim.info/
- Type: Crop/system simulation
- Use: Synthetic-but-process-based rotation rewards.

> Note: Public datasets with thousands of directly labelled farm-level optimal rotation actions are limited. Process-based simulation is a practical training-data route for this feature.

## #24 Dynamic Equipment/Logistics Routing

### Dataset 1 — Solomon VRPTW benchmark
- Link: https://www.sintef.no/projectweb/top/vrptw/solomon-benchmark/
- Type: Vehicle routing with time windows
- Use: Benchmark for routing solver and policy learning.

### Dataset 2 — CVRPLIB
- Link: http://vrp.atd-lab.inf.puc-rio.br/index.php/en/
- Type: Vehicle routing benchmarks
- Use: Large-scale routing experiments.

### Dataset 3 — OpenStreetMap
- Link: https://www.openstreetmap.org/
- Type: Real road network / geospatial data
- Use: Farm-to-market road graph and travel-cost features.

## #25 Federated Learning Across Farms

### Dataset 1 — LEAF
- Link: https://leaf.cmu.edu/
- Type: Federated learning benchmark suite
- Use: Non-IID / client-partitioned baseline experiments.

### Dataset 2 — FedML datasets/resources
- Link: https://fedml.ai/
- Type: Federated ML datasets and benchmarks
- Use: Federated training infrastructure validation.

### Dataset 3 — Agriculture datasets from #4/#16/#18
- Links: See PlantVillage, CYCleSS and SoilHealthDB above.
- Use: Partition records by farm, region or field into simulated clients.

> Note: A large public dataset explicitly partitioned across real farms with privacy-preserving federated metadata is uncommon; client partitioning of public agricultural data is the recommended reproducible demonstration setup.

## #26 Learned Buyer-Farmer Matching

### Dataset 1 — UN Comtrade
- Link: https://comtradeplus.un.org/
- Type: Global trade flows
- Use: Commodity demand/supply relationships and market matching signals.

### Dataset 2 — FAOSTAT Trade
- Link: https://www.fao.org/faostat/en/#data/TCL
- Use: Agricultural commodity trade flows.

### Dataset 3 — India Open Government Data
- Link: https://www.data.gov.in/
- Use: Market, commodity, geography and price context to engineer buyer/farmer matching features.

> Note: Public labelled buyer↔farmer transaction-pair datasets are scarce. Trade/market data are suitable proxies; your private marketplace transaction history would be the strongest supervised dataset.

## #27 Counterfactual “What-If” Simulator

### Dataset 1 — DSSAT
- Link: https://dssat.net/
- Use: Mechanistic counterfactuals for crop/weather/input scenarios.

### Dataset 2 — APSIM
- Link: https://www.apsim.info/
- Use: Process-based scenarios for fertilizer, planting date, weather and management changes.

### Dataset 3 — AgMIP
- Link: https://agmip.org/
- Use: Climate/crop scenario datasets and model outputs.

> Note: For counterfactual ML, labelled factual→counterfactual pairs are uncommon; simulation provides controlled interventions and ground-truth outcomes.

## #28 Anomaly Detection for Fraud/Quality

### Dataset 1 — MVTec AD
- Link: https://www.mvtec.com/company/research/datasets/mvtec-ad
- Type: Industrial visual anomaly detection
- Use: Baseline image anomaly detection.

### Dataset 2 — UCI Credit Card Fraud Detection
- Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- Type: Transaction fraud
- Use: Tabular fraud anomaly baseline.

### Dataset 3 — Kaggle agricultural anomaly datasets
- Link: https://www.kaggle.com/search?q=agriculture+anomaly+detection
- Use: Domain-specific supplements where license permits.

## #29 Climate Risk Scoring per Field

### Dataset 1 — WorldClim 2.1
- Link: https://www.worldclim.org/data/worldclim21.html
- Type: Global climate normals
- Modalities: Raster
- Use: Baseline temperature/precipitation risk indicators.

### Dataset 2 — ERA5-Land
- Link: https://cds.climate.copernicus.eu/datasets/reanalysis-era5-land
- Use: Historical weather extremes and temporal risk features.

### Dataset 3 — NASA GPM IMERG
- Link: https://gpm.nasa.gov/data/imerg
- Type: Satellite precipitation
- Use: Flood/drought precipitation-risk signals.

## #40 Variable-Rate Application Engine

### Dataset 1 — USDA CropScape / CDL
- Link: https://nassgeodata.gmu.edu/CropScape/
- Use: Crop zoning and field context.

### Dataset 2 — SoilGrids
- Link: https://soilgrids.org/
- Use: Soil spatial covariates for rate recommendation.

### Dataset 3 — Sentinel-2
- Link: https://dataspace.copernicus.eu/
- Use: NDVI/NDRE and spatial crop-vigor features.

> Note: Truly labelled prescription maps (recommended input rate + yield response) are less common publicly. Public raster + soil + yield datasets can be joined to create zone-level training examples.

## #44 AI-Recommended Inputs & Delivery

### Dataset 1 — FAOSTAT Fertilizers by Product
- Link: https://www.fao.org/faostat/en/
- Type: Fertilizer use statistics
- Use: Input-demand priors and regional feature engineering.

### Dataset 2 — Kaggle Crop Recommendation Dataset
- Link: https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
- Use: Map crop/soil conditions to recommended inputs.

### Dataset 3 — USDA/NASS agricultural statistics
- Link: https://quickstats.nass.usda.gov/
- Use: Regional crop/input context.

## #48 CEA Energy Optimization

### Dataset 1 — UMass/Greenhouse energy datasets via research repositories
- Link: https://www.kaggle.com/search?q=greenhouse+energy
- Type: Greenhouse climate/energy datasets
- Use: HVAC and environmental optimization baselines.

### Dataset 2 — ASHRAE Great Energy Predictor datasets
- Link: https://www.kaggle.com/c/ashrae-energy-prediction
- Type: Building energy consumption
- Use: Generic energy optimization/controller benchmarking.

### Dataset 3 — Greenhouse climate datasets via Zenodo
- Link: https://zenodo.org/search?q=greenhouse%20energy%20temperature
- Type: Research greenhouse sensor/energy data
- Use: CEA-specific features; verify individual dataset licenses.

> Note: Public CEA datasets often provide sensors but not an optimization policy label. OR-Tools can optimize on measured/simulated energy cost.

## #50 Farm Credit & Alternative-Data Loan Marketplace

### Dataset 1 — World Bank Global Findex
- Link: https://www.worldbank.org/en/publication/globalfindex
- Type: Financial inclusion survey data
- Use: Credit-access and financial-behaviour context.

### Dataset 2 — UCI German Credit Data
- Link: https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data
- Type: Credit risk classification
- Use: Baseline credit-modeling pipeline.

### Dataset 3 — World Bank Agriculture / Climate Indicators
- Link: https://data.worldbank.org/topic/agriculture-and-rural-development
- Use: Macro agricultural covariates and risk factors.

> Note: Public labelled farm-loan repayment datasets are limited. Do not claim domain-specific credit performance from generic consumer-credit datasets; use them for algorithm prototyping only.

## #51 Livestock & Dairy Health Management

### Dataset 1 — Kaggle Cow Lumpy Skin Disease / Cattle Disease Image Datasets
- Link: https://www.kaggle.com/search?q=cattle+disease+image
- Type: Veterinary images
- Use: Disease classification/CV fallback.

### Dataset 2 — Animal Disease / Livestock Image Search
- Link: https://huggingface.co/datasets?search=livestock%20disease
- Type: Image datasets where available
- Use: Supplemental animal-health classification.

### Dataset 3 — FAOSTAT Livestock
- Link: https://www.fao.org/faostat/en/#data/QCL
- Type: Livestock population/production statistics
- Use: Herd-level risk and production context.

> Note: Animal disease image datasets are fragmented and often small; for production use, combine vetted veterinary records with image data and expert labels.

## #55 Institutional & Retail B2B Sales Channel

### Dataset 1 — UN Comtrade
- Link: https://comtradeplus.un.org/
- Use: Buyer-country/commodity demand proxy.

### Dataset 2 — FAOSTAT Trade
- Link: https://www.fao.org/faostat/en/#data/TCL
- Use: Commodity flows and trade destinations.

### Dataset 3 — Open Government India market datasets
- Link: https://www.data.gov.in/
- Use: Indian commodity/market demand and price signals.

> The strongest eventual training set is the project's own transaction history: farmer, product, quantity, buyer segment, location, price, fulfilment and outcome.

## #56 Community Pest & Disease Surveillance Network

### Dataset 1 — PlantVillage
- Link: https://github.com/spMohanty/PlantVillage-Dataset
- Use: Disease classifier evidence feeding surveillance reports.

### Dataset 2 — FAO Locust Watch
- Link: https://www.fao.org/locust-watch/
- Use: Community/regional pest outbreak evidence.

### Dataset 3 — GBIF
- Link: https://www.gbif.org/
- Type: Global biodiversity/species observations
- Use: Species occurrence and geospatial context for surveillance models.

### Dataset 4 — iNaturalist
- Link: https://www.inaturalist.org/
- Type: Community observations with images/location
- Use: Supplemental community image evidence where permitted by dataset licence terms.

## Reuse Matrix

Some sources intentionally support several features:

| Dataset/source | Main features |
|---|---|
| PlantVillage | #4, #56 |
| CYCleSS | #16, #29, #27 (scenario augmentation) |
| Yellow River irrigation dataset | #3, #17 |
| FAOSTAT | #2, #9, #15, #16, #17, #19, #20, #26, #44, #51, #55 |
| Sentinel-2 / Copernicus | #11, #16, #17, #29, #40 |
| ERA5-Land | #3, #16, #17, #20, #29 |
| SoilGrids | #2, #18, #29, #40, #44 |
| DSSAT / APSIM / AgMIP | #23, #27 |
| OpenStreetMap | #24 |
| Trade data (UN Comtrade/FAOSTAT) | #26, #55 |
