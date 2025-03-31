# Dynamic VM Allocation

Dynamic VM Allocation is an innovative solution for optimizing virtual machine allocation by predicting resource demands, clustering similar tasks, and optimizing capacity through a Genetic Algorithm. This project is designed to ensure efficient resource utilization in dynamic and scalable environments.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Dependencies](#dependencies)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview
This project integrates multiple advanced techniques:
- **Demand Prediction:** Uses LightGBM to forecast resource requirements.
- **Task Clustering:** Utilizes HDBSCAN to group similar tasks.
- **Capacity Optimization:** Employs a Genetic Algorithm (via DEAP) to optimize VM capacity and container allocation.

The goal is to dynamically adjust virtual machine resources to meet fluctuating demands while minimizing energy consumption.

## Features
- **Automated Data Acquisition:** Downloads and preprocesses the dataset directly from cloud storage.
- **Advanced Prediction Model:** Leverages LightGBM for accurate demand prediction.
- **Effective Clustering:** Implements HDBSCAN to group tasks based on key metrics.
- **Optimized Resource Allocation:** Uses a Genetic Algorithm to determine the optimal configuration for VM capacity and container count.
- **Detailed Performance Metrics:** Provides insights into cluster configurations, task rejection ratios, utilization, energy usage, and runtime performance.
