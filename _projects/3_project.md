---
layout: page
title: Weather-Coupled Topology Analysis of Texas Renewable Power Grid Using GNNs and Representation Learning
img: assets/img/projects/[P3 background] Texas_renewable_power_grid.svg
importance: 3
category: work
related_publications: true
github: https://github.com/wc23386/weatherOPF
---

📅 **Project Duration:** December 2023 – May 2024

## Overview
This project develops a novel framework for analyzing weather-dependent power grid dynamics using Graph Neural Networks (GNNs) and representation learning. By integrating weather data with power grid topology, we aim to improve the reliability and efficiency of renewable energy integration in the Texas power grid.

## Technical Implementation

### 1. Weather-Grid Coupling
- **Data Integration**:
  - ERCOT grid topology data
  - NOAA weather station measurements
  - Renewable generation time series
- **Spatial Correlation Analysis**:
  - Weather station to grid node mapping
  - Spatial interpolation for missing data points
  - Temporal alignment of weather and power data

### 2. GNN Architecture
- **Graph Structure**:
  - Nodes: Power generation/consumption points
  - Edges: Transmission lines and weather correlations
  - Features: Weather parameters and grid states
- **Learning Components**:
  - Message passing neural networks
  - Attention mechanisms for weather impact
  - Temporal convolution layers

### 3. Optimization Framework
- **Objective Functions**:
  - Power flow optimization
  - Renewable integration maximization
  - Grid stability constraints
- **Weather-Aware Constraints**:
  - Temperature-dependent line ratings
  - Wind/solar generation forecasts
  - Extreme weather contingencies

## Key Results
- Improved renewable energy forecasting accuracy by 15%
- Enhanced grid stability under extreme weather conditions
- Reduced computational complexity for real-time operations
- Developed scalable solutions for large-scale power systems

## Impact
The project contributes to:
- More reliable integration of renewable energy
- Better grid resilience against weather events
- Reduced operational costs and carbon emissions
- Enhanced power system planning capabilities

## Resources
- [💻 GitHub Repository](https://github.com/wc23386/weatherOPF)
- [📄 Research Paper](assets/img/projects/[P3_paper]-Weather-Coupled_Topology_Analysis_of_Texas_Renewable_Power_Grid_Using_GNNs_and_Representation_Learning.pdf) 