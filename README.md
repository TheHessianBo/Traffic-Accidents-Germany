# Traffic Accident Analysis in Germany

## Overview
This project analyzes traffic accident data in Germany, focusing on different accident types and locations. The goal is to uncover trends and patterns that can inform road safety measures and policy decisions. The analysis includes Exploratory Data Analysis (EDA), Machine Learning (ML) modeling, and visualization techniques to identify key insights.

## Dataset
The dataset consists of accident records categorized by:
- **Accident Types**: Personal injury, material damage, intoxication-related accidents.
- **Location**: Inside built-up areas, outside built-up areas (excluding motorways), on motorways/freeways.

Source: https://www-genesis.destatis.de/datenbank/online/url/7bac8bea

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