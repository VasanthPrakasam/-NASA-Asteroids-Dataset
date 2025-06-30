# 🚀 NASA Asteroids Classification & Threat Analysis

[![NASA Data](https://img.shields.io/badge/Data%20Source-NASA%20CNEOS-0b3d91?logo=nasa)](https://cneos.jpl.nasa.gov/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/lovishbansal123/nasa-asteroids-classification)
[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?logo=python)](https://python.org)

**Machine Learning for Planetary Defense Systems**

<img src="https://via.placeholder.com/1200x500/0f4d92/ffffff?text=Asteroid+Threat+Classification+System" alt="Project Banner" width="100%">

## 📌 Project Focus
This repository implements a **multi-class classification system** for Near-Earth Objects (NEOs) using NASA's JPL data to:

- Predict asteroid threat levels (Torino Scale)
- Identify mineral composition from spectral data
- Quantify economic value for space mining

## 🔍 Dataset Highlights
```python
# Key Features (Kaggle Version)
{
    'absolute_magnitude': 'H',        # Brightness → Size proxy
    'est_diameter': 'km',             # Average diameter
    'relative_velocity': 'km/s',      # Approach speed
    'miss_distance': 'astronomical',  # 1 AU = ~150M km
    'orbit_class': 'str',             # Apollo, Aten, etc.
    'hazardous': 'bool'               # JPL classification
}
/nasa-asteroids-classification/
├── /data/                   # Processed Kaggle dataset
├── /models/                 # Pretrained models (.pkl)
├── /notebooks/              # Jupyter notebooks
│   ├── 1_data_cleaning.ipynb
│   ├── 2_threat_classification.ipynb
│   └── 3_mineral_prediction.ipynb
└── /api/                    # Flask prediction endpoint
    ├── app.py               # POST /predict_threat_level
    └── Colabfile
