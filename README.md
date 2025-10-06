# python-geo-lab
materials for  python-geo lab

# 🗺️ Python GeoAnalysis Lab (GeoPandas)

This repository contains instructional materials for an introductory lab on **Python-based geospatial analysis** using **GeoPandas**, and related libraries.  


---

## 📚 Contents

| Folder | Description |
|:--|:--|
| `data/` | Example datasets (NYC boroughs, PATH stations) |
| `images/` | Figures used in notebooks and slides |
| `pyGIS_part1` | Jupyter/Colab notebooks with step-by-step exercises |

---

## ⚙️ Environment Setup

### 🧩 Option 1: Run on Google Colab (recommended)
All notebooks are Colab-ready — simply open using the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zoey4222/python-geo-lab)

### 💻 Option 2: Run Locally via Conda

```bash
conda create -n geo_env python=3
conda activate geo_env
conda install geopandas contextily folium matplotlib pandas shapely fiona
