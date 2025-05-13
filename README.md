# QGIS U-Space Use Case

This repository contains a QGIS project that visualizes airspace restrictions and sample drone flight routes over Spanish territory. It demonstrates how to integrate regulatory geospatial data and simulated drone operations using QGIS for analysis and visualization.

This project was developed as the final assignment for the **DSIGE** (Software Development for Geographic and Spatial Information) course at **FIB - Universitat Politècnica de Catalunya (UPC)**.

## Overview

- **Map Overlay**: Visualizes airspace usage constraints and regulatory zones based on official ENAIRE data.
- **Drone Routes**: Displays sample drone flight paths using synthetic data for demonstration purposes.
- **Animation**: Supports animated visualization of drone movements over time (via QGIS TimeManager plugin).

## Data Sources

- **Airspace Restrictions**: Obtained from ENAIRE through their ArcGIS REST API, exported as GeoJSON files. Includes:
  - `aerodromos` – Aerodromes
  - `aeromodelismo` – Model aircraft activity areas
  - `avisos` – General airspace notices
  - `notam` – Active NOTAM areas (Notice to Airmen)
  - `zg_aerodromos` – Protection zones around aerodromes
  - `zg_eac_fiz` – EAC/FIZ airspace zones
  - `zg_restringidas` – Permanently restricted zones
  - `zg_rvf` – Visual flight rules limitation zones
- **Drone Route Data**: Sample data in CSV format simulating drone positions and timestamps for animation.
