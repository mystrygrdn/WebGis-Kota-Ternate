<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d3/QGIS_logo%2C_2017.svg" width="100" alt="QGIS Logo"/>
  <img src="https://leafletjs.com/docs/images/logo.png" width="150" alt="Leaflet Logo"/>
</p>

<h1 align="center">🗺️ Interactive WebGIS: Regional Spatial Data</h1>

<p align="center">
  A high-performance interactive map built using Leaflet.js, exported from QGIS. Featuring multi-layer spatial data, measurement tools, and dynamic popups.
  <br/>
  <em>Final Project — Information Systems (S1), 2026</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Leaflet-19AD13?style=flat&logo=Leaflet&logoColor=white" alt="Leaflet"/>
  <img src="https://img.shields.io/badge/QGIS-589632?style=flat&logo=QGIS&logoColor=white" alt="QGIS"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/GIS-Spatial%20Data-blue" alt="GIS"/>
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Status"/>
</p>

---

## 📖 Project Overview

This **WebGIS** project provides an interactive platform to visualize regional administrative data, infrastructure, and land use. By utilizing the `qgis2web` plugin and custom **Leaflet.js** configurations, this map allows users to explore various spatial layers with high precision.

The system includes advanced features like highlight effects on hover, detailed attribute popups, and coordinate hashing for easy location sharing.

---

## ✨ Key Features

- **Interactive Layer Control:** Toggle between 30+ spatial layers including administration, roads, and land use.
- **Advanced Measurement Tool:** Built-in tool to measure distance (meters/km) and area (hectares) directly on the map.
- **Dynamic Feature Highlighting:** Visual feedback when hovering over administrative boundaries or landmarks.
- **Smart Popups:** Automatically filters and displays relevant data attributes from the GeoJSON datasets.
- **Google Earth Integration:** Uses high-resolution satellite imagery as the base layer.

---

## 📊 Data Layers Summary

The map categorizes spatial data into three main types:

| Layer Category | Data Included |
|---|---|
| **Administration** | District boundaries (Kecamatan), Coastal lines, Boundary pillars. |
| **Land Use (AR)** | Settlement areas, Forests, Agriculture, Shrublands, and Water bodies. |
| **Infrastructure (PT)** | Schools, Hospitals, Government offices, Ports, and Airports. |
| **Topography (LN)** | River networks, Road networks, and Elevation contours. |

---

## 🛠️ Tech Stack

- **Mapping Engine:** Leaflet.js
- **Data Source:** QGIS (processed from 50K scale regional data)
- **Base Layer:** Google Earth Satellite API
- **Plugins:** - `Leaflet-Measure` for distance/area tools.
    - `Leaflet-Hash` for URL-based location tracking.
    - `Autolinker` for clickable attribute links.
    - `L.Control.Layers.Tree` for organized layer management.

---
