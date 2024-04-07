# ASA-WEZ: A Probabilistic Weapon Engagement Zone Model for Beyond Visual Range Air Combat

## Overview
This repository contains the implementation and documentation for "ASA-WEZ", a novel probabilistic Weapon Engagement Zone (WEZ) model described in the paper "ASA-WEZ: A Probabilistic Weapon Engagement Zone Model for Beyond Visual Range Air Combat".

## Introduction
ASA-WEZ is designed to enhance the assessment of missile launch effectiveness in Beyond Visual Range (BVR) air combat scenarios. Unlike traditional models that focus on maximum, minimum, and no-escape zones, ASA-WEZ utilizes advanced machine learning techniques to predict the probability of kill based on the missile's miss distance. This model incorporates aspects of warhead lethality and probabilistic target behavior to provide a more dynamic and precise WEZ calculation.

## Model Features
- **Probabilistic Kill Estimation**: Integrates machine learning to calculate the likelihood of a kill based on various engagement parameters.
- **Dynamic Target Behavior Modeling**: Accounts for changes in target behavior during engagement to adjust the WEZ calculation in real-time.
- **High-Fidelity Simulations**: Rigorously tested using detailed simulation environments to ensure accuracy and reliability.
- **Benchmarking Against Traditional Models**: Demonstrated improvements over existing WEZ models in terms of precision and computational efficiency.

## Repository Structure
/ann - Artificial Neural Networks used for probability estimation.
/eda - Exploratory Data Analysis of the dataset and features used in the model.
/lethality - Modules related to modeling the effects of missile warhead lethality.
/pr - Polynomial Regression model for probability estimation.
/target - Code related to target behavior and dynamics modeling.
/xgboost - Implementation of the XGBoost model for probability predictions.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.