# Conditional Normalizing Flows for PDE Simulations

A lightweight, modular Machine Learning framework for building Conditional Normalizing Flows, featuring applications in Linear Elasticity and Stokes problems.

## Overview
This repository contains the core architecture for generating, training, and evaluating Conditional Normalizing Flows. It is designed to act as a surrogate model for complex physical simulations, providing rapid, probabilistic PDE solutions.

## Repository Structure
* **`src/`**: Core Python engine (model architecture, training loops, metrics, and data utilities).
* **`notebooks/`**: Jupyter Notebooks for executing and visualizing experiments (Toy Example, Elasticity, Stokes).
* **`scripts/`**: Standalone execution scripts.
* **`requirements.txt`**: Environment dependencies.

## Getting Started
1. Clone this repository to your local machine.
2. Create a virtual environment and install the required dependencies:
   ```bash
   pip install -r requirements.txt
