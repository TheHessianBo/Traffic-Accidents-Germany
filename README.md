# Traffic Accident Analysis in Germany

## Overview
This project analyzes traffic accident data in Germany, focusing on different accident types and locations. The goal is to uncover trends and patterns that can inform road safety measures and policy decisions. The analysis includes Exploratory Data Analysis (EDA), Machine Learning (ML) modeling, and visualization techniques to identify key insights.

## Dataset
The dataset consists of accident records categorized by:

- **Accident Types**:  
  - **Personal injury accidents** (inside and outside built-up areas, on motorways/freeways)  
  - **Serious accidents involving material damage**  
  - **Other accidents involving intoxication**  
  - **Other accidents involving material damage**  


- **Location Categories**:  
  - Inside built-up areas  
  - Outside built-up areas (excluding motorways/freeways)  
  - On motorways/freeways  


- Source: [Car Accidents](https://www-genesis.destatis.de/datenbank/online/url/7bac8bea)
- Files: [Car accidents tables](https://drive.google.com/drive/u/0/folders/1JmMtUwwLEHZ4KbEc4d_YM2q9-RpyLyB5)

## **Analysis Plan**
We will analyze accident data using the following approaches:

### **1. Annual Accident Trends by Location**

#### Categorization:
- **Objective**: Classify accidents by year and location.
  - **Locations**: Inside Built-Up Areas, Outside Built-Up Areas, On Motorways/Freeways.

#### Trend Analysis:
- **Objective**: Identify increases or decreases in accident rates over time.
  - Analyze the trend in accident numbers over the years to understand if the accident rate is rising or falling.

#### Accident Type Breakdown:
- **Objective**: Analyze the distribution of accident types.
  - Categorize accidents by:
    - Personal Injury
    - Serious Material Damage
    - Intoxication-Related Accidents
    - Other Material Damage

#### Influence of Speed Limits & Infrastructure:
- **Objective**: Investigate the effect of speed limits and road infrastructure on accident rates.
  - Explore how the speed limits, road conditions, and types of roads (e.g., highways vs. non-highways) correlate with accident frequency.

---

### **2. Accident Classification by Year**

#### Injury vs. Property Damage:
- **Objective**: Differentiate between accidents causing injuries and those causing only property damage.
  - Accidents are classified into:
    - Injury Accidents: Resulting in physical harm.
    - Property Damage Accidents: Only involving vehicle/property damage.

#### Overall Impact:
- **Objective**: Assess the combined impact of injuries and property damage.
  - Quantify the impact in terms of:
    - Financial Costs
    - Casualties (fatalities and injuries)

    !!!!! founded mortality datain other table.... that can be added maybe later 

---

### **3. Seasonal & Monthly Patterns**

#### Peak Accident Periods:
- **Objective**: Identify the months with the highest accident occurrences.
  - Recognize specific months when accidents are more frequent.

#### Winter vs. Summer Effects:
- **Objective**: Compare accident rates influenced by seasonal weather conditions.
  - Analyze how winter weather (ice, snow, fog) and summer travel patterns affect accident rates.

#### Holiday & Event Impact:
- **Objective**: Examine accident patterns during major holidays and events.
  - Focus on times like New Year’s Eve, Christmas, Oktoberfest, Easter, and school vacations.
  - Analyze how holidays affect accident rates.

#### Weather Influence:
- **Objective**: Correlate accidents with historical weather data.
  - Assess how weather conditions such as rain, snow, fog, and extreme temperatures affect accident rates.
  - Use weather patterns to help develop risk mitigation strategies.

---


### **4. EURO 2024 Impact**
- **More Traffic, More Accidents?**: Investigate accident frequency during major events.
- **Public Transport & Road Congestion**: Evaluate alternative transport impact.

---

### **5. Impact of COVID-19**
- **Immediate Effects (2020-2021):**
    - Fewer vehicles → fewer accidents?
    - More reckless driving on empty roads?
- **Post-COVID (2022-2024):**
   - Did traffic behavior return to normal?
   - Long-term shifts (e.g., increased remote work → fewer accidents during rush hours?)
   - Changes in public transport vs. private vehicle usage.

   ---

### **6. Machine Learning Predictions for 2024**
- **Trend Forecasting**: Use time-series models (e.g., ARIMA, LSTMs) to predict accident numbers.
- **High-Risk Periods & Locations**: Train models to predict where accidents are most likely.
- **Contributing Factors**: Feature engineering with weather, traffic, speed limits, and economic data to improve predictions.
- **Predictive Hotspot Mapping**: Use geospatial data to visualize accident-prone areas.

---

## Objectives
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) to uncover trends.
- Apply machine learning models to classify high-risk areas.
- Visualize key insights using interactive dashboards.
- Provide actionable recommendations for road safety improvements.

## Project Structure

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