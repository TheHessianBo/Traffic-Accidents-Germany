# Traffic Accident Analysis in Germany

## Overview
This project analyzes traffic accident data in Germany, focusing on different accident types and locations. The goal is to uncover trends and patterns that can inform road safety measures and policy decisions. The analysis includes Exploratory Data Analysis (EDA), Machine Learning (ML) modeling, and visualization techniques to identify key insights.

## Dataset
The dataset consists of accident records categorized by:
- **Accident Types**: Personal injury, material damage, intoxication-related accidents.
- **Location**: Inside built-up areas, outside built-up areas (excluding motorways), on motorways/freeways.

Source: [Car Accidents](https://www-genesis.destatis.de/datenbank/online/url/7bac8bea)  

## **Analysis Plan**
We will analyze accident data using the following approaches:

**1. Total Accidents by Year and Area**
- Data Aggregation: Group accidents by year and region (state/city/rural vs. urban).
- Trends: Identify long-term trends, e.g., rising or falling accident rates.
- Regional Differences: Compare accident frequencies in urban vs. rural areas.

**2. Accident Categories by Year**
- Injuries vs. Material Damage: Separate accidents with injuries from those with only property damage.
- Severity Analysis: Check for patterns in fatal vs. non-fatal accidents.
- Both Factors Combined: Look at the total impact in terms of cost and casualties.

**3. Critical Months & Seasonal Effects**
- Seasonality Analysis: Identify peaks in accidents per month.
Winter vs. Summer: Compare accident rates due to ice, fog, or tourism travel in summer.
- Holidays & Festivities: New Year's Eve, Christmas, Oktoberfest, Easter, and school holidays—do they correlate with spikes in accidents?
- Weather Correlation: Use historical weather data to see how conditions impact accidents.

**4. EURO 2024 Impact**
- More Traffic, More Accidents?: During major events, are accidents more frequent?
- City-Specific Impact: Host cities vs. other locations.
- Time of Day Effects: Are accidents more common before or after matches?

**5. Impact of COVID-19**
- Immediate Effects (2020-2021):
    - Fewer cars → fewer accidents?
    - More reckless driving on empty roads?
- Post-COVID (2022-2024):
   - Did traffic behavior return to normal?
   - Long-term shifts (e.g., more remote work → fewer accidents in rush hours?)

**6. Machine Learning Predictions for 2024**
- Trend Forecasting: Use time-series models (e.g., ARIMA, LSTMs) to predict accident numbers.
- High-Risk Periods & Locations: Train a model to predict where accidents are most likely.
- Contributing Factors: Feature engineering with weather, traffic, and economic data to improve predictions.


## Objectives
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) to uncover trends.
- Apply machine learning models to classify high-risk areas.
- Visualize key insights using interactive dashboards.
- Provide actionable recommendations for road safety improvements.

## Project Structure
```
traffic_accident_analysis/
│── data/                # Raw and processed data
│── README.md            # Project documentation
│── requirements.txt     # Required dependencies
```

## Installation
To set up the environment, use:
```sh
pip install -r requirements.txt
```

## Usage
1. **Run EDA**: Explore the dataset using the provided Jupyter notebooks.
2. **Train Model**: train and evaluate machine learning models.
3. **Visualize Results**: Generate reports (and dashboards) for insights.

## Machine Learning Approach
- Feature Engineering (accident frequency, severity scores, location impact)
- Clustering (K-Means, DBSCAN) to detect accident hotspots
- Classification (Random Forest, XGBoost) to predict accident severity

## Results & Insights
- Identification of high-risk accident zones.
- Key factors influencing accident severity.
- Data-driven recommendations for improving traffic safety.

## Contributors
- Milos Mirkovic, Sebastian Wegstein

## License
MIT License
# Traffic-Accidents-Germany