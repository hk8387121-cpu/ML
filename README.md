# Agri ML Dataset Catalog — 33 ML Features

This repository is the dataset source-of-truth for the agriculture platform's **33 ML / hybrid-ML features**.

Every feature has its **own section and dataset links**. Repeated datasets across features are intentional where the same source supports multiple models.

## Feature Coverage

| # | Feature | ML Type | Dataset folder |
|---:|---|---|---|
| 2 | AI Crop Planning | Supervised / recommendation | `features/02_ai_crop_planning/` |
| 3 | Smart Irrigation | Regression / forecasting | `features/03_smart_irrigation/` |
| 4 | Crop Health AI | Computer vision | `features/04_crop_health_ai/` |
| 9 | Harvest & Market | Forecasting / ranking | `features/09_harvest_market/` |
| 11 | Satellite Crop Stress Prediction | Remote sensing | `features/11_satellite_crop_stress/` |
| 12 | Drone/Video Plant Counting | Object detection | `features/12_drone_plant_counting/` |
| 13 | Weed Species Classification | Classification / detection | `features/13_weed_species/` |
| 14 | Grain Quality Scoring | Vision / quality classification | `features/14_grain_quality/` |
| 15 | Hyperlocal Mandi Price Forecasting | Time-series | `features/15_mandi_price_forecasting/` |
| 16 | Yield Forecasting with Uncertainty | Time-series / probabilistic ML | `features/16_yield_forecasting/` |
| 17 | Water Demand Forecasting | Time-series / regression | `features/17_water_demand_forecasting/` |
| 18 | Soil Health Modeling | Regression / Gaussian Process | `features/18_soil_health/` |
| 19 | Variety Recommendation Engine | Recommendation / ranking | `features/19_variety_recommendation/` |
| 20 | Pest Outbreak Spread Prediction | Spatiotemporal / simulation | `features/20_pest_outbreak_spread/` |
| 21 | Voice-First AI Assistant | Speech / NLP | `features/21_voice_ai_assistant/` |
| 22 | Multimodal Query Understanding | Vision-language | `features/22_multimodal_query/` |
| 23 | RL Crop Rotation Planner | Reinforcement learning | `features/23_rl_crop_rotation/` |
| 24 | Dynamic Equipment/Logistics Routing | Optimization / ML hybrid | `features/24_dynamic_routing/` |
| 25 | Federated Learning Across Farms | Federated ML | `features/25_federated_learning/` |
| 26 | Learned Buyer-Farmer Matching | Recommendation / ranking | `features/26_buyer_farmer_matching/` |
| 27 | Counterfactual What-If Simulator | Causal / counterfactual ML | `features/27_counterfactual_simulator/` |
| 28 | Anomaly Detection for Fraud/Quality | Anomaly detection | `features/28_anomaly_detection/` |
| 29 | Climate Risk Scoring per Field | Climate / geospatial ML | `features/29_climate_risk/` |
| 40 | Variable-Rate Application Engine | Spatial ML | `features/40_variable_rate_application/` |
| 44 | AI-Recommended Inputs & Delivery | Ranking / recommendation | `features/44_input_recommendation/` |
| 48 | CEA Energy Optimization | Optimization / ML hybrid | `features/48_cea_energy_optimization/` |
| 50 | Farm Credit & Alternative-Data Loan Marketplace | Credit ML | `features/50_farm_credit/` |
| 51 | Livestock & Dairy Health Management | Vision / classification | `features/51_livestock_health/` |
| 55 | Institutional & Retail B2B Sales Channel | Recommendation / ranking | `features/55_b2b_sales/` |
| 56 | Community Pest & Disease Surveillance Network | Aggregation / ML | `features/56_pest_surveillance/` |

## Master files

- `MASTER_DATASETS.md` — human-readable catalog with all feature-by-feature links.
- `datasets.csv` — machine-readable dataset index.
- `datasets.json` — machine-readable structured metadata.

## Dataset policy

1. Prefer official, research, government and established dataset repositories.
2. Clearly mark synthetic/demo data where real public data is not available.
3. Keep source links separate by feature, even when a dataset repeats.
4. Verify the dataset landing page before using it in a production pipeline.
5. Respect the license, attribution and access terms of every dataset.

## Highlighted verified sources

- PlantVillage: https://github.com/spMohanty/PlantVillage-Dataset
- CYCleSS yield dataset: https://springernature.figshare.com/articles/dataset/CYCleSS_the_Crop_Yields_Climate_Soils_and_Satellites_Dataset/27225807
- Yellow River Basin irrigation-demand dataset: https://zenodo.org/records/18628324
- URC UAV rice plant-counting dataset: https://ngdc.cncb.ac.cn/opia/dataset/datasets?dataId=4
- Weed25: https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2022.1053329/full
- GrainSet: https://github.com/hellodfan/GrainSet
- SoilHealthDB: https://agdatacommons.nal.usda.gov/articles/dataset/Data_from_A_database_for_global_soil_health_assessment/24853500
- Kaggle New Plant Diseases: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
- Mozilla Common Voice: https://commonvoice.mozilla.org/en/datasets
- MS COCO: https://cocodataset.org/
- Visual Question Answering: https://visualqa.org/
- MVTec AD: https://www.mvtec.com/company/research/datasets/mvtec-ad
- WorldClim: https://www.worldclim.org/data/worldclim21.html
- CropScape: https://nassgeodata.gmu.edu/CropScape/
- India Open Government Data: https://www.data.gov.in/
