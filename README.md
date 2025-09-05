### 🌍 GEOWATCH – Early Warning System for GLOFs

An AI-powered web application for Glacier Lake Outburst Flood (GLOF) prediction and impact assessment.
The system integrates satellite imagery, meteorological data, and deep learning models to provide early warnings and support climate risk analysis.

### 🚀 Features

**📡 Satellite Data Integration** : Uses MODIS meteorological data and Landsat-8 imagery.

**🗺️ Geospatial Analysis**: Preprocessing and mapping with QGIS; computes NDWI, NDSI, and DEM-based terrain analysis.

**🤖 AI Forecasting**: TensorFlow model for time-series prediction, achieving MSE = 0.6.

**⚠️ Anomaly Detection**: Predicts future anomalies and overlays them on geospatial layers.

**🌊 Flood Impact Mapping**: Generates early warnings and visual impact assessments of potentially affected areas.

**🌐 Web Application**: Interactive dashboard for data visualization and risk monitoring.

### 📊 Tech Stack

Languages: Python

Libraries/Frameworks: TensorFlow, NumPy, Pandas, Matplotlib, Rasterio, GDAL

GIS Tools: QGIS, DEM analysis

Data Sources: MODIS, Landsat-8

Web Framework: (Flask / Django / Streamlit – whichever you used)

### 🔬 Workflow

Data Collection – Fetch MODIS meteorological data & Landsat-8 imagery.

Preprocessing – Apply QGIS/GDAL workflows, extract NDWI, NDSI, and DEM features.

Model Training – Train TensorFlow time-series forecasting model on historical data.

Prediction & Overlay – Forecast anomalies and overlay them on geospatial maps.

Visualization – Serve results in a web dashboard for decision-making.
