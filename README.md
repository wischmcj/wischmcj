# Collin Wischmeyer 
<!-- <img src="./imgs/skeletor_whole_ds20_proj_alphapt1.png" alt="canopy hydrodynamics visualization" width="270" align="right"/> -->

I'm a **data engineer** and **environmental data enthusiast** passionate about empowering scientists with data. My largest side projects focus on 
- Remote sensing data analysis and publishing related research 
- Using infrastructure-as-code tools for the orchestration and containerization of workflows
- Webscraping and archiving




## 🔬 Projects at a Glance
| Section                              | Technologies                                                                 | Project                                                                                      |
|---------------------------------------|-------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| **Infrastructure-as-Code**   | *Ansible, Terraform, Bash*                        | **ml_ops_tree_learn**: [Object detection MLOps](#-ml_ops_tree_learn) |
|  | *Prometheus, Grafana, NodeJS, Docker*                 | **ArchiveTeam IaC**: [Distributed compute observation stack](#-archiveteam-observation-stack) |
| **Geospatial & Remote Sensing**       |  *Open3D, PyTorch, OpenCV, Rasterio*               | **pyqsm**: [Image processing and spatial algorithms](#-pyqsm) |
|      | *NumPy, MatPlotLib, GeoPandas, GDAL*                   |  **canopyHydrodynamics**: [Simulating water movement within tree canopies](#-canopyhydrodynamics) |
| **Data Engineering / DevOps**         | *DLT, DuckDB, Web Scraping, Streamlit*                            | **LinkedInScraper**: [Automated data acquisition](#-LinkedInScraper)                         |
|    | *GitOps,  Pandocs, PyPI*                     |  **canopyHydrodynamics**: [Robust GitOps CI/CD workflows ](#-canopyhydrodynamics) |




## 🚀 Featured Projects

> [!NOTE]
> Detailed project descriptions are available via dropdowns.

### 🌳 [`canopyHydrodynamics`](https://github.com/wischmcj/canopyHydrodynamics)
<em> GitOps, NumPy, MatPlotLib, GeoPandas, GDAL, Pandocs, PyPI </em>
<p>
<img src="./imgs/PC_QSM_Plot.png" alt="canopy hydrodynamics visualization" width="400"/>
</p>

<details>
<summary>  
 Simulating water movement within tree canopiea under varied meteorological conditions.
 </summary>
- LiDAR data is used to derive graph based structural models
- This package is the subject of multiple research papers published in peer-reviewed journals for ecological research.
- Extracts data for ecohydrological modeling from terrestrial lidar point clouds.
</details>

<details>
<summary>  
Leverages GitOps for robust CI/CD capabilities.
</summary>
 Includes:
<ul>
<li> automated linting and testing for all changes
</li>
<li> dynamically created version upgrade branches
</li>
<li>auto-generated method documentation 
</li>
<li>Versioned deployment automated for release branches </li>
</ul>
</details>

---

### 🌲 [`ArchiveTeam Observation Stack`](https://github.com/wischmcj/archiveteam-digitalocean-IaC)
<em>Prometheus, Grafana, NodeJS, Docker, Bash</em>
<p>
<img src="./imgs/archiveteam_small.png" alt="at_observation_process" width="400"/>
</p>
<details>
<summary>  
Infrastructure-as-code to provision and configure a multi-server, multi-container cluster with a modern observability stack. Utilized for the community archive project <a href="https://wiki.archiveteam.org/">ArchiveTeam</a>.
</summary>
Consists of:
<ul>
  <li>
    Docker containerization monitored by CloudWatch
  </li>
  <li>Prometheus for node management/aggregation
  </li>
  <li>Graphana dashboards for visualization
  </li>
  <li>a custom a node.js metrics server for exporting telemetry. 
  </li>
</ul>
</details>

---

### 🌲 [`pyQSM`](https://github.com/wischmcj/pyQSM)
<em>SciPy, Open3D OpenCV, Rasterio </em> 
<p>
<img src="./imgs/cluster4_side_by_Side.png" alt="pyqsm_example_isolation" width="400"/>
</p>

<details>
<summary>  
Image processing and spatial algorithms to clean and segment trees and their components within terrestrial LiDAR point clouds.
</summary> 
</ul>
Key functionality includes:
<li>Tree Isolation: Separating individual trees from surrounding man-made objects and other vegetation.
</li>
<li>Epiphyte Segmentation: Isolating and analyzing different parts of trees (trunk, branches, leaves) as well as plants in and around the trees.
</li>
<li>Ray Casting Similations: Creation of 3D meshes representing objects and examining their characteristics via tensor intersection calculations.
</li>
</ul>
</details>

---

### 🔄 [`ml_ops_tree_learn`](https://github.com/wischmcj/ml_ops_tree_learn)
<em> Laspy, Terraform, PyTorch, Open3D </em>
<p>
<img src="./imgs/isolated_forest_floor.png" alt="object_isolated_w_mlo-tl" width="400"/>
</p>
<details>
<summary>  
  An MLOps pipeline for configuration and deployment of a convolutional neural-net on GPU-enabled, cloud-hosted clusters.
</summary> 
  Automates the provisioning of Digital Ocean GPU droplets to allow users to leverage CUDA friendly compute. Designed as a 'one-click' solution enabling researchers without specialized hardware to process LiDAR data at minimal cost. 
</details>

---

### 🕸️ [`linkedInScraper`](https://github.com/wischmcj/linkedInScraper)
<em>DLT, DuckDB, Web Scraping, Streamlit </em> 
<p>
<img src="./imgs/li_scraper_ui.png" alt="LI Scraper Streamlit UI]" width="400"/>
</p>

<details>
<summary>  
A DLT pipeline leveraging a LinkedIn's 'hidden' Voyager API to retrieve job and company data.
</summary> 
<ul>
  <li>Built on DLT which provides a UI for viewing pipeline status, exploring data
  </li>
  <li>Custom DLT source automatically handles REST requests, pagination, data extraction and relational DB storage
  </li>
  <li>Predefined endpoints/available datasets
    - `get_companies`: scrape followed companies via GraphQL profile components
    - `get_job_urls`: fetch job cards per company
    - `get_descriptions`: fetch job descriptions and details
    </li>
  <li> Extensible, with additional resources configured via json
  </li>
</ul>
</details>

📫 Feel free to connect with me:  
[LinkedIn](https://www.linkedin.com/in/collin-wischmeyer-b55659a4) • [GitHub](https://github.com/wischmcj) • cjwischmeyer@gmail.com  
<p>
  <p>
    <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
    <img src="https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=Amazon-AWS&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Terraform-623CE4?style=flat-square&logo=Terraform&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=Kubernetes&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Prefect-3C4E62?style=flat-square&logo=Prefect&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Open%20Source-181717?style=flat-square&logo=GitHub&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Research-6A1B9A?style=flat-square&logo=ResearchGate&logoColor=white"/>
    <img src="https://img.shields.io/badge/-PyPI-3775A9?style=flat-square&logo=PyPI&logoColor=white"/>
    <img src="https://img.shields.io/badge/-LiDAR-00C853?style=flat-square&logo=Cloudsmith&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/>
    <img src="https://img.shields.io/badge/-CI%2FCD-2088FF?style=flat-square&logo=GitHub-Actions&logoColor=white"/>
  </p>
</p>
<p>
