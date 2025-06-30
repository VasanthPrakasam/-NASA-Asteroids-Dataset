# 🌌 NASA Asteroids Dataset Analysis

[![NASA Open Data](https://img.shields.io/badge/Data%20Source-NASA%20Open%20Data-0b3d91?logo=nasa)](https://data.nasa.gov/Space-Science/Near-Earth-Asteroids/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://python.org)
[![License](https://img.shields.io/badge/License-NASA%20Open%20Data%20Agreement-lightgrey)](https://data.nasa.gov/docs/license.html)

**Machine Learning for Planetary Defense & Space Resource Identification**

<img src="https://via.placeholder.com/800x400/0f4d92/ffffff?text=Asteroid+Risk+Assessment+Dashboard" alt="Asteroid Risk Heatmap" width="100%">

## 📌 Project Focus
This repository transforms NASA's Near-Earth Object (NEO) data into actionable insights for:
- **Hazard prediction** (Earth-impact risk modeling)
- **Space mining potential** (mineral composition analysis)
- **Orbital trajectory forecasting** (DL time-series)

## 🛠️ Tech Stack
| Category        | Tools                                                                 |
|-----------------|----------------------------------------------------------------------|
| **Core**        | Python 3.8+, SQL                                                     |
| **ML/DL**       | Scikit-learn, XGBoost, TensorFlow (CNNs/RNNs)                       |
| **Visualization**| Plotly, Matplotlib, PowerBI                                         |
| **Deployment**  | Flask API, Docker, AWS Lambda                                       |

## 🗂 Dataset Features
Key variables analyzed:
```python
# Critical Features
nasa_asteroids = {
    'diameter': 'km',                  # Size estimation
    'miss_distance': 'LD',             # Lunar Distance (1 LD = 384,400 km)
    'velocity': 'km/s',                # Relative speed
    'is_hazardous': 'bool',            # JPL classification
    'spectral_type': 'str',            # Composition (S-type, C-type, etc.)
    'orbital_period': 'days'           # Revolution time
}
