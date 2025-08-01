# 🌍 Searching for Earth-like Worlds
A data science project exploring NASA's exoplanet data to identify Earth-like planets using visualization and clustering techniques.


## 🚀 Project Overview

This project explores a dataset of confirmed exoplanets from NASA’s Exoplanet Archive to identify Earth-like worlds — planets similar to Earth in terms of size, temperature, and potential habitability. Using Python and data science tools, we visualize trends and apply clustering techniques to discover promising Earth analogs.

---

## 📊 Dataset

The dataset is sourced directly from [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/). It contains variables such as:

- **Planet Radius (`pl_rade`)** — in Earth radii  
- **Planet Mass (`pl_bmasse`)** — in Earth masses  
- **Equilibrium Temperature (`pl_eqt`)** — in Kelvin  
- **Orbital Period (`pl_orbper`)**  
- **Distance from Earth (`sy_dist`)** — in parsecs  
- **Discovery Method & Year**

Only planets with complete data across key variables were used in the final analysis.

---

## 🛠️ Techniques Used

- **Data Cleaning** with Pandas
- **Data Visualization** with Matplotlib & Seaborn
- **Clustering** with K-Means
- **Feature Scaling** with StandardScaler

---

## 📈 Key Insights

- Clustering helped identify groups of potentially habitable planets.
- Visualizations revealed trends in discovery methods and distances.
- Earth-like candidates were selected based on similarity in radius, mass, and temperature.

---

## 📁 File Structure

```bash
📦earth-like-worlds
 ┣ 📜 notebook.ipynb      # The main Colab notebook
 ┗ 📜 README.md           # Project documentation (this file)
