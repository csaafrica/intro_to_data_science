# CSA 2025 Data Science Project Topics

**Expected Deliverables for All Projects**: A report outlining the problem, what was done and why, data sources used, technical details of analysis/modelling (e.g. models used and why), results and interpretation of the results, recommendations for action, limitations of current work and expectations for future work.

## Project 1: Agricultural Productivity and Climate Resilience Dashboard [Group 6]

**Problem Statement:** Climate change threatens food security across East Africa. 
Analyze how weather patterns affect crop yields and identify resilient farming regions.

**Data Sources:**
- FAOSTAT (crop production data): [crop production data](https://www.fao.org/faostat/)
- Climate Hazards Group (CHIRPS rainfall): [CHIRPS rainfall](https://www.chc.ucsb.edu/data/chirps)
- World Bank Climate Change Knowledge Portal: [Climate Change Data](https://data.worldbank.org/topic/19)

**Deliverables:**
1. Interactive dashboard showing crop yield trends vs rainfall patterns (2000-2023)
2. Regression model predicting maize/wheat yields based on precipitation and temperature
3. Risk map identifying climate-vulnerable agricultural regions
4. Technical report (see above).

**Technical Requirements:**
- Use pandas for merging climate and crop data
- Create choropleth maps using folium/plotly
- Implement multiple linear regression and random forest models
- Compare model performance using R², RMSE

---

## Project 2: Healthcare Access Inequality Predictor [Group 1]

**Problem Statement:** Identify underserved populations and predict healthcare access challenges to guide health facility placement.

**Data Sources:**
- DHS Program StatCompiler: [DHS Program StatCompiler](https://www.statcompiler.com/)
- WHO Global Health Observatory: [Data portal](https://www.who.int/data)
- OpenStreetMap (health facility locations via Overpass API)

**Deliverables:**
1. Healthcare access score for each region (combining distance, facility density, health outcomes)
2. Classification model predicting low/medium/high healthcare access
3. Interactive map showing healthcare deserts
4. Technical report/policy brief on optimal locations for new health facilities

**Technical Requirements:**
- Calculate distance matrices using geopy
- Feature engineering: create accessibility indices
- Implement logistic regression and decision tree classifiers
- Use SHAP values to explain model predictions

---

## Project 3: Mobile Money Financial Inclusion Analyzer [Groups 7, 10]

**Problem Statement:** Despite M-Pesa's success, financial exclusion persists. Identify barriers and predict adoption likelihood.

**Data Sources:**
- World Bank Global Findex Database (2011-2021): [Database](https://www.worldbank.org/en/publication/globalfindex)
- GSMA Mobile Money Deployment Tracker: [GSMA website](https://www.gsma.com/solutions-and-impact/connectivity-for-good/mobile-for-development/m4d-tracker/mobile-money-deployment-tracker/)
- FinAccess Household Survey (Kenya): [Report](https://www.centralbank.go.ke/wp-content/uploads/2024/12/2024-FINACCESS-HOUSEHOLD-SURVEY-MAIN-REPORT.pdf)

**Deliverables:**
1. Time series visualization of mobile money adoption across East Africa
2. Classification model predicting mobile money usage
3. Barrier analysis dashboard (age, gender, education, rural/urban)
4. Technical report and actionable recommendations for increasing adoption

**Technical Requirements:**
- Handle missing data using appropriate imputation
- Create interactive plotly dashboards
- Implement Random Forest and XGBoost classifiers
- Perform feature importance analysis

---

## Project 4: Education Quality and Outcome Predictor [Groups 9, 15]

**Problem Statement:** Education quality varies drastically. Predict student performance and identify factors affecting learning outcomes.

**Data Sources:**
- UNESCO Institute for Statistics: [website](http://data.uis.unesco.org/)
- Kenya Open Data (KCPE/KCSE results): [Kenya data portal](https://kenya.opendataforafrica.org)
- DHS Education Data: [Data](https://dhsprogram.com/data/)

**Deliverables:**
1. School performance dashboard by county/region
2. Regression model predicting exam scores based on school resources
3. Gender disparity analysis in STEM subjects
4. Technical report/intervention priority matrix for education officials

**Technical Requirements:**
- Web scraping for exam results (BeautifulSoup)
- Hierarchical clustering for school grouping
- Ridge/Lasso regression for prediction
- Create Sankey diagrams for education pathways

---

## Project 5: Urban Air Quality Health Impact Assessor

**Problem Statement:** Air pollution in Nairobi, Kampala, and Dodoma causes significant health issues. Quantify the impact and predict high-risk areas. Start with Nairobi.

**Data Sources:**
- OpenAQ API (real-time air quality): [Website](https://openaq.org/)
- WHO Ambient Air Quality Database: [Link](https://www.who.int/data/gho/data/themes/air-pollution/who-air-quality-database)
- Local health ministry respiratory disease statistics

**Deliverables:**
1. Real-time air quality dashboard for major cities
2. Regression model linking PM2.5 levels to respiratory admissions
3. Health cost calculator for air pollution
4. Clean air action plan with predicted impact

**Technical Requirements:**
- API integration for live data updates
- Time series analysis with seasonal decomposition
- Polynomial regression for non-linear relationships
- Bootstrap confidence intervals for health impact estimates

---

## Project 6: Climate-Smart Agriculture Recommender [Groups 4, 11]

**Problem Statement:** Farmers need guidance on crop selection as climate patterns shift. Build a recommendation system for climate-appropriate crops.

**Data Sources:**
- FAO Global Agro-Ecological Zones: [Data portal](https://gaez.fao.org)
- Climate.gov historical weather data: [NOAA data portal](https://www.climate.gov/maps-data/dataset/past-weather-zip-code-data-table)
- Market price data from regional commodity exchanges

**Deliverables:**
1. Crop suitability maps under current and projected climate
2. Recommendation engine for crop selection
3. Profit optimization model including climate risk
4. Farmer decision-support tool prototype
5. Technical report

**Technical Requirements:**
- Implement collaborative filtering for recommendations
- Use Random Forest for suitability classification
- Monte Carlo simulation for risk analysis
- Create interactive Streamlit app

---

## Project 7: Maternal and Child Health Risk Stratification [Group 13]

**Problem Statement:** Reduce maternal and infant mortality by identifying high-risk pregnancies early.

**Data Sources:**
- DHS Program (detailed health surveys): [Data portal](https://dhsprogram.com/data/)
- WHO Global Health Observatory: [Data portal](https://www.who.int/data)
- UNICEF Data Warehouse: [Data warehouse](https://data.unicef.org/resources/data_explorer/unicef_f/)

**Deliverables:**
1. Risk scoring algorithm for pregnant women
2. Predictive model for adverse outcomes
3. Resource allocation optimizer for health facilities
4. Mobile-friendly risk assessment tool design
5. Technical report

**Technical Requirements:**
- Handle class imbalance with SMOTE
- Implement ensemble methods (voting classifier)
- Create risk stratification tiers
- Design API endpoint for risk calculator

---

## Project 8: Food Security Early Warning System [Groups 8, 17]

**Problem Statement:** Predict food crises before they occur to enable timely interventions.

**Data Sources:**
- FEWS NET Data Portal: [US Gov website](https://www.google.com/search?client=safari&rls=en&q=FEWS+NET+Data+Portal&ie=UTF-8&oe=UTF-8)
- FAO Food Price Monitoring: [FAO Link](https://www.fao.org/giews/food-prices/home/en/)
- ACLED Conflict Data: [Armed Conflict data link](https://acleddata.com)
- CHIRPS Rainfall Data: [Portal](https://www.chc.ucsb.edu/data/chirps)

**Deliverables:**
1. Food security risk dashboard with 3-month predictions
2. Multi-class classification model (secure/stressed/crisis/emergency)
3. Alert system design with trigger thresholds
4. Intervention effectiveness analyzer
5. Technical report


**Technical Requirements:**
- Implement time-lagged features (rainfall, prices, conflict events)
- Use Random Forest or XGBoost for classification
- Create automated alert generation
- Design evaluation metrics for early warning systems

---

## Project 9: Renewable Energy Potential Analyzer [Group 12]

**Problem Statement:** Accelerate renewable energy adoption by identifying high-potential locations and predicting project success.

**Data Sources:**
- Global Solar Atlas / Global Wind Atlas: [Link](https://globalsolaratlas.info)
- World Bank Electricity Access Database: [Access database](https://www.google.com/search?client=safari&rls=en&q=World+Bank+Electricity+Access+Database&ie=UTF-8&oe=UTF-8)
- NASA POWER (weather/climate data): [Info link](https://power.larc.nasa.gov)

**Deliverables:**
1. Renewable energy potential maps (solar/wind/hydro)
2. Site suitability classification model
3. Cost-benefit analysis tool
4. Investment opportunity ranker

**Technical Requirements:**
- Raster data processing with rasterio
- Implement gradient boosting for site classification
- Financial modeling (NPV, IRR calculations)
- Create interactive investment dashboard

---

## Project 10: Digital Economy Growth Tracker [Group 2]

**Problem Statement:** The digital economy drives growth but develops unevenly. Track progress and predict digital transformation success.

**Data Sources:**
- ITU ICT Development Index: [Index page](https://www.itu.int/en/ITU-D/Statistics/Pages/IDI/default.aspx)
- GSMA Mobile Connectivity Index: [Index](https://www.mobileconnectivityindex.com/index.html)
- World Bank Digital Adoption Index: [Info](https://www.worldbank.org/en/publication/wdr2016/Digital-Adoption-Index)
- Google Trends API (technology adoption): [Info](https://trends.google.com/trends/)

**Deliverables:**
1. Digital maturity assessment framework
2. Regression model predicting digital economy growth
3. Digital divide visualization dashboard
4. Policy roadmap for digital transformation

**Technical Requirements:**
- Composite index creation using PCA
- Implement panel data regression
- Network analysis for digital ecosystems
- Create predictive scenarios using Monte Carlo

---

## Project 11: Drought Resilience and Water Security Predictor

**Problem Statement:** Water scarcity affects millions. Predict water stress and identify communities needing urgent intervention.

**Data Sources:**
- USGS FEWS NET Water Point Data: [Water point portal](https://earlywarning.usgs.gov/fews/waterpoint/)
- MODIS Normalized Difference Vegetation Index (NDVI): [MODIS NVDI](https://modis.gsfc.nasa.gov/data/dataprod/mod13.php)
- CHIRPS Rainfall Data: [Portal](https://www.chc.ucsb.edu/data/chirps)
- Water Point Data Exchange (WPdx): [Link](https://www.waterpointdata.org)

**Deliverables:**
1. Water stress prediction model (3-6 month horizon)
2. Community vulnerability index and map
3. Water point functionality classifier
4. Drought intervention priority ranker

**Technical Requirements:**
- Engineer lagged features (rainfall, NDVI values)
- Logistic regression for functionality classification
- Random Forest for vulnerability prediction
- Gradient boosting for water stress levels
- Real-time drought monitoring dashboard

---

## Project 12: Informal Economy Formalization Potential Assessor

**Problem Statement:** The informal sector employs 80%+ but lacks protection and growth potential. Identify formalization opportunities.

**Data Sources:**
- ILO Informal Economy Database: [Stats on informal economy](https://ilostat.ilo.org/topics/informality/)
- World Bank Enterprise Surveys: [Data portal](https://www.enterprisesurveys.org/en/data)
- Mobile money transaction data (aggregated): [Kenya](https://www.centralbank.go.ke/national-payments-system/mobile-payments/)
- OpenStreetMap (market/business locations): 

**Deliverables:**
1. Informal sector size estimator by region/sector
2. Formalization readiness classifier
3. Tax revenue potential calculator
4. Formalization pathway recommendation engine

**Technical Requirements:**
- Geospatial clustering for market identification
- Logistic regression for formalization likelihood
- Linear regression for revenue projections
- Category encoding for business types
- Interactive policy simulation tool

---

## Project 13: Cross-Border Trade Flow Optimizer

**Problem Statement:** Intra-African trade remains below 20% despite AfCFTA. Identify bottlenecks and predict trade flow improvements.

**Data Sources:**
- UN COMTRADE Database: [COMTRADE](https://comtrade.un.org/)
- World Bank Trading Across Borders data: [Archive](https://archive.doingbusiness.org/en/data/exploretopics/trading-across-borders)
- AfDB Regional Integration Index: [Info](https://arii.uneca.org)
- Google Maps API (border crossing times)

**Deliverables:**
1. Trade flow visualization network for East Africa
2. Regression model predicting bilateral trade volumes
3. Border efficiency classifier (efficient/moderate/inefficient)
4. Trade corridor optimization recommendations

**Technical Requirements:**
- Network analysis with networkx
- Linear regression for trade flow prediction
- Random Forest for border classification
- Interactive Sankey diagrams for trade flows
- API integration for real-time border data

---

## General Project Guidelines

**Required Python Libraries:**
- Data manipulation: pandas, numpy
- Visualization: matplotlib, seaborn, plotly, folium
- Machine learning: scikit-learn, xgboost
- APIs: requests, beautifulsoup4
- Geospatial: geopandas, shapely

**Evaluation Criteria:**
- Data quality and preprocessing (25%)
- Model performance and validation (25%)
- Visualization quality and insights (25%)
- Report: real-world understanding of the problem, applicability within a local context and recommendations (25%)
