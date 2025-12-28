# Badre Abderrahmane Alloul
**Geospatial Software Engineer & Computational Hydrologist**  
*Lyon, France*

[![Portfolio](https://img.shields.io/badge/Portfolio-00d4aa?style=for-the-badge&logo=google-earth&logoColor=white)](https://badibosspy.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077b5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/badre-abderrahmane-alloul)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:badrallouldjazairi@gmail.com)

---

### 🌐 Engineering Ecosystem
I build software systems that combine satellite remote sensing with hydrological modeling. My work focuses on processing multi-spectral imagery and running physics-based simulations to support water resource management and flood risk assessment.

```mermaid
graph LR
    subgraph Data["Data Sources"]
        A1[Sentinel-2]
        A2[ERA5 Climate]
        A3[Field Sensors]
    end

    subgraph Process["Processing"]
        B1[Image Segmentation]
        B2[Hydrological Models]
        B3[Statistical Analysis]
    end

    subgraph Infra["Infrastructure"]
        C1[Dask Clusters]
        C2[Cloud Storage]
    end

    subgraph Output["Applications"]
        D1[Flood Mapping]
        D2[Water Resources]
    end

    A1 --> B1
    A2 --> B2
    A3 --> B3
    B1 --> C1
    B2 --> C1
    B3 --> C1
    C1 --> C2
    C2 --> D1
    C2 --> D2
```

---

### 🔬 Current Learning & Development
I'm currently expanding my skills in several areas:
- **Deep Learning for Satellite Imagery**: Working with PyTorch and TorchGeo to build image segmentation models (U-Net, DeepLabv3+) for land cover classification. Training on Sentinel-2 data to detect water bodies and vegetation changes.
- **Cloud Infrastructure**: Deploying computational workflows on AWS and Google Cloud. Learning to optimize costs while processing large raster datasets (multi-TB) using cloud-optimized formats like COG and STAC catalogs.
- **Physics-Based Machine Learning**: Experimenting with ways to incorporate hydrological equations into neural networks, though this is still early-stage work for me.

---

### 🔧 Technical Skills

#### 🌍 Geospatial & Remote Sensing
![GDAL](https://img.shields.io/badge/GDAL-00d4aa?style=flat-square) 
![Rasterio](https://img.shields.io/badge/Rasterio-00d4aa?style=flat-square) 
![GeoPandas](https://img.shields.io/badge/GeoPandas-00d4aa?style=flat-square) 
![QGIS](https://img.shields.io/badge/QGIS-00d4aa?style=flat-square&logo=qgis&logoColor=white) 
![GEE](https://img.shields.io/badge/Earth_Engine-00d4aa?style=flat-square&logo=google&logoColor=white) 
![STAC](https://img.shields.io/badge/STAC-00d4aa?style=flat-square)

#### 🌊 Hydrology & Environmental Modeling
- **Simulation Tools**: Wflow, TELEMAC-2D, ANUGA, HEC-RAS
- **Analysis**: Extreme value statistics (GEV distributions), intensity-duration-frequency curves, vegetation indices (NDVI, EVI)
- **Applications**: Flood modeling, hydropower assessment, agricultural water management

#### 🤖 Programming & Data Science
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) 
![xarray](https://img.shields.io/badge/xarray-00d4aa?style=flat-square) 
![Dask](https://img.shields.io/badge/Dask-00d4aa?style=flat-square) 
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

#### 🗄️ Databases & Cloud Platforms
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) 
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square) 
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) 
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

### 💼 What I'm Working On
I design and implement geospatial data pipelines for environmental monitoring. This includes writing Python code to process satellite imagery, setting up PostgreSQL/PostGIS databases for spatial queries, and configuring cloud infrastructure to handle large datasets efficiently. My goal is to make remote sensing data more accessible for water resource planning and disaster preparedness.

For more examples of my work, visit my [portfolio](https://badibosspy.github.io) or connect on [LinkedIn](https://linkedin.com/in/badre-abderrahmane-alloul).
