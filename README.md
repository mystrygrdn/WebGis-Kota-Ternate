<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/qgis/qgis-original.svg" width="80" alt="QGIS Logo"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/leaflet/leaflet-original.svg" width="100" alt="Leaflet Logo"/>
</p>

<h1 align="center">🗺️ Interactive WebGIS: Regional Spatial Data</h1>

<p align="center">
  A high-performance interactive map built using Leaflet.js, exported from QGIS. Featuring multi-layer spatial data, measurement tools, and dynamic popups.
  <br/>
  <em>Final Project — Information Systems (S1), 2026</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Leaflet-19AD13?style=for-the-badge&logo=Leaflet&logoColor=white" alt="Leaflet"/>
  <img src="https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=QGIS&logoColor=white" alt="QGIS"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

---

## 📖 Project Overview

This **WebGIS** project provides an interactive platform to visualize regional administrative data, infrastructure, and land use. By utilizing the `qgis2web` plugin and custom **Leaflet.js** configurations, this map allows users to explore various spatial layers with high precision.

The system includes advanced features like highlight effects on hover, detailed attribute popups, and coordinate hashing for easy location sharing.

---

## ✨ Key Features

- **Interactive Layer Control:** Toggle between 30+ spatial layers including administration, roads, and land use.
- **Advanced Measurement Tool:** Built-in tool to measure distance (meters/km) and area (hectares) langsung di peta.
- **Dynamic Feature Highlighting:** Visual feedback saat kursor berada di atas batas administrasi atau objek penting.
- **Smart Popups:** Otomatis memfilter dan menampilkan atribut data dari dataset GeoJSON.
- **Google Earth Integration:** Menggunakan citra satelit resolusi tinggi sebagai base layer.

---

## 📊 Data Layers Summary

Proyek ini mencakup data spasial yang terbagi dalam beberapa kategori utama:

| Layer Category | Data Included |
|---|---|
| **Administration** | Batas Kecamatan, Garis Pantai, Pilar Batas. |
| **Land Use (AR)** | Pemukiman, Hutan, Pertanian, Semak Belukar, dan Perairan. |
| **Infrastructure (PT)** | Sarana Pendidikan, RS/Puskesmas, Kantor Pemerintahan, Pelabuhan, & Bandara. |
| **Topography (LN)** | Jaringan Sungai, Jaringan Jalan, dan Garis Kontur. |

---

## 🛠️ Tech Stack

- **Mapping Engine:** Leaflet.js
- **Data Source:** QGIS (processed from 50K scale regional data)
- **Base Layer:** Google Earth Satellite API
- **Plugins:** - `Leaflet-Measure` (Tool pengukur)
    - `Leaflet-Hash` (URL tracking)
    - `Autolinker` (Clickable links)
    - `L.Control.Layers.Tree` (Manajemen layer)
