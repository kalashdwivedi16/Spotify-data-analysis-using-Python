#  Spotify Data Analysis

**Author:** *Kalash Dwivedi*  
**Notebook:** `Spotify Data Analysis.ipynb`  
**Datasets:** `tracks.csv`, `SpotifyFeatures.csv`  

---

## Project Overview

This repository contains an **exploratory data analysis (EDA)** project on Spotify track metadata and audio features.  
The goal is to understand **distributions, relationships, and trends** in musical attributes (e.g., *energy, danceability, loudness*), identify top tracks and artists, explore **duration and popularity**, and analyze **temporal patterns** such as release years.

The analysis uses:
- Descriptive statistics  
- Visualizations  
- Regression plots  

…to surface insights for **music analytics** and **recommendation ideas**.

---

##  What’s Included

| File | Description |
|------|--------------|
| `Spotify Data Analysis.ipynb` | Jupyter Notebook containing the full analysis (loading, cleaning, visualizations, merging datasets, and interpretation). |
| `tracks.csv` | Spotify track metadata — includes `id`, `name`, `artists`, `release_date`, `popularity`, and feature columns. |
| `SpotifyFeatures.csv` | Audio feature dataset — includes `track_id`, `genre`, and audio attributes. |
| `README.md` | This file — project description, usage guide, and process overview. |

---

## Tools & Libraries

The project uses standard Python data-science libraries:

- **Python 3.8+**
- `pandas` — data manipulation and I/O  
- `numpy` — numerical operations  
- `matplotlib` — basic plotting  
- `seaborn` — statistical visualizations  
- `plotly` — interactive charts *(optional)*  
- `nbformat` — for notebook operations *(optional)*

### Installation
pip install pandas numpy matplotlib seaborn plotly
