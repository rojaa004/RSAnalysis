# 🌍 RSAnalysis

**RSAnalysis** is a FastAPI-powered backend application for remote sensing data analysis using Google Earth Engine. It provides a RESTful API and a simple frontend interface for users to submit GeoJSON polygons, select date ranges, and choose datasets like SRTM DEM, CHIRPS Rainfall, and MODIS NDVI.

---

## 🚀 Features

- Accepts GeoJSON polygons as Area of Interest (AOI)
- Supports custom date ranges
- Integrates multiple Earth observation datasets:
  - SRTM Elevation
  - CHIRPS Daily Rainfall
  - MODIS NDVI
- REST API built with FastAPI
- HTML frontend for easy form-based input
- JSON response with processed results

---

## 🛠️ Technologies Used

- FastAPI
- Google Earth Engine Python API
- Jinja2 for templating
- HTML + JavaScript frontend

---

## 📁 Project Structure
RSAnalysis/ ├── Agri_analysis.ipynb               # FastAPI backend ├── index.html        # Frontend form ── style.css         


## 🛠️ Outputs
Geotiff files
CSV files - statistics


**Authenticate Earth Engine** - earthengine authenticate

**Acknowledgement**
- Google Earth Engine
- FastAPI community
- CHIRPS, MODIS, and SRTM data providers

## Author
** Roja A** - @rojaa004


