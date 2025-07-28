# CSA 2025 Data Science Project Topics

## Project 1: Agricultural Productivity & Climate Resilience Dashboard

**Problem Statement:** Climate change threatens food security across East Africa. 
Analyze how weather patterns affect crop yields and identify resilient farming regions.

**Data Sources:**
- FAOSTAT (crop production data): https://www.fao.org/faostat/
- Climate Hazards Group (CHIRPS rainfall): https://www.chc.ucsb.edu/data/chirps
- World Bank Climate Change Knowledge Portal

**Deliverables:**
1. Interactive dashboard showing crop yield trends vs rainfall patterns (2000-2023)
2. Regression model predicting maize/wheat yields based on precipitation and temperature
3. Risk map identifying climate-vulnerable agricultural regions
4. 5-page report with recommendations for climate adaptation

**Technical Requirements:**
- Use pandas for merging climate and crop data
- Create choropleth maps using folium/plotly
- Implement multiple linear regression and random forest models
- Compare model performance using R², RMSE

---

## Project 2: Healthcare Access Inequality Predictor

**Problem Statement:** Identify underserved populations and predict healthcare access challenges to guide health facility placement.

**Data Sources:**
- DHS Program StatCompiler: https://www.statcompiler.com/
- WHO Global Health Observatory
- OpenStreetMap (health facility locations via Overpass API)

**Deliverables:**
1. Healthcare access score for each region (combining distance, facility density, health outcomes)
2. Classification model predicting low/medium/high healthcare access
3. Interactive map showing healthcare deserts
4. Policy brief on optimal locations for new health facilities

**Technical Requirements:**
- Calculate distance matrices using geopy
- Feature engineering: create accessibility indices
- Implement logistic regression and decision tree classifiers
- Use SHAP values to explain model predictions

---

## Project 3: Mobile Money Financial Inclusion Analyzer

**Problem Statement:** Despite M-Pesa's success, financial exclusion persists. Identify barriers and predict adoption likelihood.

**Data Sources:**
- World Bank Global Findex Database (2011-2021)
- GSMA Mobile Money Deployment Tracker
- FinAccess Household Survey (Kenya)

**Deliverables:**
1. Time series visualization of mobile money adoption across East Africa
2. Classification model predicting mobile money usage
3. Barrier analysis dashboard (age, gender, education, rural/urban)
4. Actionable recommendations for increasing adoption

**Technical Requirements:**
- Handle missing data using appropriate imputation
- Create interactive plotly dashboards
- Implement Random Forest and XGBoost classifiers
- Perform feature importance analysis

---

## Project 4: Education Quality & Outcome Predictor

**Problem Statement:** Education quality varies drastically. Predict student performance and identify factors affecting learning outcomes.

**Data Sources:**
- UNESCO Institute for Statistics: http://data.uis.unesco.org/
- Kenya Open Data (KCPE/KCSE results)
- DHS Education Data

**Deliverables:**
1. School performance dashboard by county/region
2. Regression model predicting exam scores based on school resources
3. Gender disparity analysis in STEM subjects
4. Intervention priority matrix for education officials

**Technical Requirements:**
- Web scraping for exam results (BeautifulSoup)
- Hierarchical clustering for school grouping
- Ridge/Lasso regression for prediction
- Create Sankey diagrams for education pathways

---

## Project 5: Urban Air Quality Health Impact Assessor

**Problem Statement:** Air pollution in Nairobi, Kampala, and Addis Ababa causes significant health issues. Quantify the impact and predict high-risk areas.

**Data Sources:**
- OpenAQ API (real-time air quality): https://openaq.org/
- WHO Ambient Air Quality Database
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

## Project 6: Youth Employment Opportunity Mapper

**Problem Statement:** Youth unemployment exceeds 20% in many regions. Match skills with opportunities and predict employment success.

**Data Sources:**
- ILO ILOSTAT: https://ilostat.ilo.org/
- LinkedIn Economic Graph (aggregated data)
- National employment surveys

**Deliverables:**
1. Skills gap analysis dashboard
2. Job matching algorithm (classification model)
3. Regional employment heat map
4. Youth employment strategy recommendations

**Technical Requirements:**
- Natural language processing for job descriptions
- Implement k-NN and SVM classifiers
- Create network graphs of skills-jobs relationships
- A/B testing framework for intervention strategies

---

## Project 7: Climate-Smart Agriculture Recommender

**Problem Statement:** Farmers need guidance on crop selection as climate patterns shift. Build a recommendation system for climate-appropriate crops.

**Data Sources:**
- FAO Global Agro-Ecological Zones
- Climate.gov historical weather data
- Market price data from regional commodity exchanges

**Deliverables:**
1. Crop suitability maps under current and projected climate
2. Recommendation engine for crop selection
3. Profit optimization model including climate risk
4. Farmer decision-support tool prototype

**Technical Requirements:**
- Implement collaborative filtering for recommendations
- Use Random Forest for suitability classification
- Monte Carlo simulation for risk analysis
- Create interactive Streamlit app

---

## Project 8: Maternal & Child Health Risk Stratification

**Problem Statement:** Reduce maternal and infant mortality by identifying high-risk pregnancies early.

**Data Sources:**
- DHS Program (detailed health surveys)
- WHO Global Health Observatory
- UNICEF Data Warehouse

**Deliverables:**
1. Risk scoring algorithm for pregnant women
2. Predictive model for adverse outcomes
3. Resource allocation optimizer for health facilities
4. Mobile-friendly risk assessment tool design

**Technical Requirements:**
- Handle class imbalance with SMOTE
- Implement ensemble methods (voting classifier)
- Create risk stratification tiers
- Design API endpoint for risk calculator

---

## Project 9: Infrastructure Investment Prioritization Model

**Problem Statement:** Limited budgets require smart infrastructure investments. Prioritize projects with maximum development impact.

**Data Sources:**
- World Bank Infrastructure Database
- OpenStreetMap (via Overpass API)
- AfDB Infrastructure Development Index

**Deliverables:**
1. Infrastructure deficit analysis by region
2. Economic impact prediction model
3. Investment prioritization algorithm
4. Interactive scenario planning tool

**Technical Requirements:**
- Graph analysis for transport networks
- Multi-criteria decision analysis (MCDA)
- Linear programming for budget optimization
- Sensitivity analysis for recommendations

---

## Project 10: Food Security Early Warning System

**Problem Statement:** Predict food crises before they occur to enable timely interventions.

**Data Sources:**
- FEWS NET Data Portal
- FAO Food Price Monitoring
- ACLED Conflict Data
- CHIRPS Rainfall Data

**Deliverables:**
1. Food security risk dashboard with 3-month predictions
2. Multi-class classification model (secure/stressed/crisis/emergency)
3. Alert system design with trigger thresholds
4. Intervention effectiveness analyzer

**Technical Requirements:**
- Implement time-lagged features
- Use LSTM or gradient boosting for prediction
- Create automated alert generation
- Design evaluation metrics for early warning systems

---

## Project 11: Renewable Energy Potential Analyzer

**Problem Statement:** Accelerate renewable energy adoption by identifying high-potential locations and predicting project success.

**Data Sources:**
- Global Solar Atlas / Global Wind Atlas
- World Bank Electricity Access Database
- NASA POWER (weather/climate data)

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

## Project 12: Digital Economy Growth Tracker

**Problem Statement:** The digital economy drives growth but develops unevenly. Track progress and predict digital transformation success.

**Data Sources:**
- ITU ICT Development Index
- GSMA Mobile Connectivity Index
- World Bank Digital Adoption Index
- Google Trends API (technology adoption)

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

## General Project Guidelines

**Each team should:**
1. Spend Day 1 on data collection, cleaning, and EDA
2. Days 2-3 on modeling and analysis
3. Day 4 on visualization and dashboard creation
4. Day 5 on report writing and presentation prep

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
- Real-world applicability and recommendations (25%)
