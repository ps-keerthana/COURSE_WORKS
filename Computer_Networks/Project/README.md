# SMARTGUARD  
**Repository:** https://github.com/ps-keerthana/SMARTGUARD

## Overview
SmartGuard is a simulation-based centralized monitoring system designed for campus environments. It collects and analyzes real-time environmental data including temperature, humidity, light, and CO₂ levels from simulated classrooms and laboratories.

A virtual network of **100 Mininet-hosted sensor clients** generates continuous readings and publishes them via **MQTT** to a central broker. Two backend services a **data collector** and an **anomaly detector** subscribe to the broker, process incoming data, and store information in **InfluxDB**.

SmartGuard provides insights through a dashboard built using **Dash** and Grafana, featuring:

- Real-time heatmaps  
- Time-series trend visualizations  
- Live anomaly alerts  

This system demonstrates efficient centralized monitoring and scalable data handling with seamless integration of networking, simulation, and analytics components.
