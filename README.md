# Flood Prediction

## Overview
Flood Prediction is a Python-based project that utilizes real-time data from APIs to predict the likelihood of flooding based on rainfall and water level metrics. The goal of this project is to provide an accessible and efficient way to assess flood risks in various regions, helping communities prepare and respond effectively.

## Features
- **Data Retrieval**: Fetches real-time rainfall and water level data using public APIs.
- **Data Analysis**: Analyzes the relationship between rainfall percentages, water levels, and flood occurrence.
- **Machine Learning Model**: Implements a logistic regression model to predict flood events based on input data.
- **Visualization**: Provides visual representations of data trends and prediction outcomes using Matplotlib and Seaborn.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Requests (for API calls)

## Installation
To set up the project, clone this repository and install the required libraries:

```bash
git clone https://github.com/AaryaGurav/flood-prediction.git
cd flood-prediction
pip install -r requirements.txt
```
## Usage
Run the main script and follow the prompts to enter a location for rainfall and water level checks. The program will display the current water levels and predict whether a flood is expected.
```bash
python flood_prediction.py
```

## Contribution
Contributions are welcome! Please open an issue or submit a pull request for any improvements or features you'd like to see.




