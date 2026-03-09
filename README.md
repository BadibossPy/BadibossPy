### Badre Abderrahmane Alloul
**Geospatial Solutions Architect | Computational Hydrologist**
*Lyon, France*

[![Portfolio](https://img.shields.io/badge/Architecture_Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://badibosspy.github.io)
[![LinkedIn](https://img.shields.io/badge/Connect-0077b5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/badre-abderrahmane-alloul)
[![Email](https://img.shields.io/badge/Collaborate-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:badrallouldjazairi@gmail.com)

---

### 🌐 The Computational Synthesis

I engineer **production-grade environmental systems**. My work bridges the gap between **Physical Simulation** (PDE solvers) and **Artificial Intelligence** (Stochastic inference).

Most environmental workflows are static and fragmented. I build **persistent, auto-calibrating digital twins**. I design architectures where satellite telemetry forces hydrological models in real-time, scaled via HPC and Cloud infrastructure. I do not just run models; I architect the pipelines that make them operational, reproducible, and scalable.

---

### 📐 System Topology: The Hybrid Architecture

My core architectural pattern integrates deterministic physics with data-driven ML. This topology handles the velocity of Earth Observation data without compromising physical consistency.

```mermaid
flowchart TD
    subgraph L1 ["I. DATA INGESTION (STAC/ETL)"]
        A1[("Sentinel-1/2 (SAR/MSI)")]
        A2[("ERA5 / CMIP6 Reanalysis")]
        A3[("In-Situ Telemetry")]
    end

    subgraph L2 ["II. THE HYBRID KERNEL"]
        direction LR
        B1["Latent Space Mapping (TorchGeo)"]
        B2["Physics-Informed ML (PINNs)"]
        B3["Numerical Solvers (TELEMAC/Wflow)"]
        B1 --> B2
        B2 <--> B3
    end

    subgraph L3 ["III. DISTRIBUTED COMPUTE"]
        C1["Dask / xarray Orchestration"]
        C2["HPC Kernels (SLURM/MPI)"]
    end

    subgraph L4 ["IV. OPERATIONAL DELIVERY"]
        D1["Vector Tile Services"]
        D2["Decision Support Systems"]
    end

    A1 & A2 & A3 -->|Normalized Stream| B1
    B3 -->|State Vector| C1
    C1 <--> C2
    C1 -->|Zarr/COG| D1 & D2

    style L2 fill:#0d1117,stroke:#00d4aa,stroke-width:2px,color:#fff
    style C1 stroke:#d2a8ff,stroke-width:2px
```

---

### 🔬 Engineering Focus

I operate at the intersection of **Physics, Code, and Infrastructure**:

1.  **Hybrid Modeling (Physics + AI):** Moving beyond black-box ML. I embed physical constraints (mass conservation, momentum) into neural networks to create robust predictors for data-scarce environments.
2.  **HPC & Cloud Scalability:** Designing "compute-agnostic" pipelines that run seamlessly on on-premise SLURM clusters or AWS Fargate. I optimize for I/O bottlenecks using lazy loading (Dask) and cloud-native formats (Zarr/COG).
3.  **Automated Calibration:** Replacing manual parameter tuning with differentiable programming. Using gradient-based optimization to auto-calibrate hydrological parameters (Manning’s *n*, conductivity) against real-time observation.

---

### 🔧 Technological Arsenal

#### 🌍 Geospatial Core
*The foundational layer for spatial manipulation.*
![GDAL](https://img.shields.io/badge/GDAL/OGR-C++_Bindings-00d4aa?style=flat-square)
![Rasterio](https://img.shields.io/badge/Rasterio/Shapely-Low_Level_Ops-00d4aa?style=flat-square)
![PostGIS](https://img.shields.io/badge/PostGIS-Spatial_SQL_Optimization-336791?style=flat-square&logo=postgresql&logoColor=white)
![QGIS](https://img.shields.io/badge/PyQGIS-Plugin_Dev-00d4aa?style=flat-square&logo=qgis&logoColor=white)

#### 🌊 Simulation & Physics
*Deterministic solvers for fluid dynamics and hydrology.*
![Solvers](https://img.shields.io/badge/Solvers-TELEMAC_2D_|_Wflow_SBM_|_HEC_RAS-000000?style=flat-square)
![Methodology](https://img.shields.io/badge/Methods-Finite_Volume_|_Mesh_Generation_|_Boundary_Conditions-000000?style=flat-square)

#### 🤖 Intelligence & Compute
*Stochastic modeling and distributed processing.*
![Python](https://img.shields.io/badge/Python-Scientific_Stack-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-TorchGeo_|_DeepLabv3+-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scale](https://img.shields.io/badge/Scale-xarray_|_Dask_|_Zarr-563D7C?style=flat-square&logo=dask&logoColor=white)

#### ☁️ Infrastructure & DevOps
*Reproducibility and deployment.*
![Docker](https://img.shields.io/badge/Containerization-Docker_|_Singularity-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloud](https://img.shields.io/badge/Cloud-AWS_|_BigQuery_|_SLURM-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

### 🎨 Philosophy

> *"Code is the modern notation for physical law."*

I advocate for **Open Science** as a strict engineering requirement. Environmental models must be version-controlled, containerized, and documented to withstand scrutiny. If it cannot be re-run from scratch by a third party, it is not science—it is an anecdote.

[**Explore Architecture Portfolio →**](https://badibosspy.github.io)
