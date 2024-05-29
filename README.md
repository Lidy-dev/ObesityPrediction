## Overview
This repository contains a machine learning project focused on predicting the weight of individuals based on their daily water consumption, eating habits, and physical activity frequency. The dataset includes data collected from individuals in Mexico, Peru, and Colombia, aged between 14 and 61.

## Dataset Description
The dataset comprises 17 attributes and 2111 records, but the primary focus is on the following features:
- **CH2O (Consumption of water daily):** Indicates how often participants consume water, categorized as Frequently, Sometimes, Always, and No.
- **CAEC (Consumption of food between meals):** Indicates the frequency of eating between meals.
- **FAF (Physical activity frequency):** Indicates how often participants engage in physical activities.

The target variable for prediction is:
- **Weight:** The weight of participants.

The dataset provides comprehensive information on participants' eating habits, physical condition, and demographic details, enabling the development of accurate predictive models.

## Project Goals
- Develop predictive models to estimate the weight of participants using machine learning algorithms.
- Utilize regression techniques to analyze the relationship between the features and the target variable.
- Evaluate model performance using appropriate metrics.

## Project Structure
The repository is organized as follows:
- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks with data exploration, preprocessing, and model development steps.
- `src/`: Source code for data processing and model training.
- `README.md`: Project overview and setup instructions.
- `requirements.txt`: List of dependencies required for the project.
