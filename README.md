# PoKER: A Probability of Kill Estimation Rate Model for Air-to-Air Missiles Using Machine Learning on Stochastic Targets

## Overview
This repository contains the implementation and documentation for "PoKER", a novel probabilistic Weapon Engagement Zone (WEZ) model described in the paper "PoKER: A Probability of Kill Estimation Rate Model for Air-to-Air Missiles Using Machine Learning Against Stochastic Targets".

## Overview

## Introduction
PoKER is designed to enhance the assessment of missile launch effectiveness in Beyond Visual Range (BVR) air combat scenarios. Unlike traditional models that focus on maximum, minimum, and no-escape zones,PoKER utilizes advanced machine learning techniques to predict the probability of kill based on the missile's miss distance. This model incorporates aspects of warhead lethality and probabilistic target behavior to provide a more dynamic and precise WEZ calculation.

## Model Features
- **Probabilistic Kill Estimation**: Integrates machine learning to calculate the likelihood of a kill based on various engagement parameters.
- **Dynamic Target Behavior Modeling**: Accounts for changes in target behavior during engagement to adjust the WEZ calculation in real-time.
- **High-Fidelity Simulations**: Rigorously tested using detailed simulation environments to ensure accuracy and reliability.
- **Benchmarking Against Traditional Models**: Demonstrated improvements over existing WEZ models in terms of precision and computational efficiency.

## Repository Structure
- `/ann` - Contains Artificial Neural Networks that estimate kill probabilities.
- `/eda` - Provides tools for Exploratory Data Analysis of the dataset and features integral to the model.
- `/lethality` - Includes modules that simulate the impact of missile warhead lethality.
- `/pr` - Features a Polynomial Regression model for refining probability estimations.
- `/target` - Hosts scripts for modeling the dynamics of target behavior.
- `/xgboost` - Implements the XGBoost algorithm for enhanced predictive accuracy.

## License
This project is distributed under the MIT License. For more details, please refer to the `LICENSE.md` file included in this repository.
