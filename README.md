# 🛰️ Interactive Satellite Imagery Downloader using Leafmap

This Python notebook enables users to **interactively select a region of interest (ROI)** on a satellite basemap and download high-resolution satellite imagery as a GeoTIFF file. It's especially useful for **remote sensing**, **machine learning model training**, **land cover analysis**, and other **geospatial applications**.

---

## 🌍 Features

- 🗺️ Interactive map display using **Leafmap**  
- 📦 Easy installation of all required libraries  
- 🔲 ROI selection via map-based drawing tool  
- 📥 Downloads satellite imagery (Google Satellite) as a **GeoTIFF**  
- 🧭 Centered on **Kathmandu**, with customizable location  
- 🖼️ Adds downloaded image back to map for visualization  

---

## 🔧 Requirements

Install the required Python packages (run this inside your notebook or terminal):

```bash
pip install leafmap segment-geospatial localtileserver
