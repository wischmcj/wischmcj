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
  📣 Have any questions? Please reach out!:<br/>
  <a href="mailto:cjwischmeyer@gmail.com?subject=[GitHub]%20Contact&body=Hello%20CJ%2C%0A%0AI%20am%20reaching%20out%20after%20seeing%20your%20GitHub%20profile"><img src="https://img.shields.io/badge/e‑mail-D14836.svg?style=for-the-badge&logo=GMail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/collin-wischmeyer-b55659a4/"><img src="https://img.shields.io/badge/linkedin-0077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <!-- <a href="https://twitter.com/mrstandu33"><img src="https://img.shields.io/badge/twitter-1DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white"/></a> -->
</p>

I'm a **data engineer** and **environmental data enthusiast** passionate about empowering scientists with data. My key efforts focus on geospatial/remote sensing data analysis but I add value more generally through:
- the creation of data acquisition pipelines (REST/SOAP Apis, web scraping,...)
- implementation of lightweight CI/CD tooling
- orchestration and containerization of workflows (often leveraging IaC tools for reproducibility)

---

## 🔬 My Work at a Glance

### CI/CD, Production Code
- **canopyHydrodynamics**  
  *Python, NumPy, GeoPandas, NetworkX, PyPI, GitHub Actions*  
  Simulates water movement through tree canopies using LiDAR and spatial hydrology models.

### Spatial Data
- **pyQSM**  
  *Python, Open3D, PyTorch, Mesh Processing Libraries*  
  Processes terrestrial LiDAR scans for tree isolation and segmentation using ML and procedural techniques.

### IaC, Cloud Infra
- **ArchiveTeam IAC**  
  *OpenTofu, Ansible, Docker, Prometheus, Grafana, NodeJS*  
  Infrastructure-as-code for deploying observability stacks and containerized apps across remote machines.

- **PenguaLab-IaC**  
  *Terraform, Ansible, Helm, Kubernetes (k3s)*  
  Home lab infrastructure-as-code for distributed modeling and resilient, flexible tooling.

### ML Ops
- **ml_ops_tree_learn**  
  *Python, Digital Ocean, CUDA, MLOps*  
  Cloud deployment tool for the Tree Learn Unet model with automated GPU provisioning.


- ⚙️ **TODO

---

## 🚀 Featured Projects

### 🌳 [`canopyHydrodynamics`](https://github.com/wischmcj/canopyHydrodynamics)
A production-grade Python package for simulating water movement through tree canopies using LiDAR data and spatial hydrology models.

- Published to PyPI and cited in ecological research
- Extracts data for ecohydrological modeling utilizing only commonly used packages (NumPy, GeoPandas, NetworkX)
- Completed with robust CI/CD for testing, documentation automation and package publication

![canopy hydrodynamics visualization](./imgs/PC_QSM_Plot.png)

---

### 🌲 [`pyQSM`](https://github.com/wischmcj/pyQSM)
An under-development tool for processing terrestrial LiDAR scans; combining ML and procdedural techniqes for two main purposes
  1. **Tree Isolation**: Separating individual trees from surrounding man-made objects and other vegetation
  2. **Tree Segmentation**: Isolating and analyzing different parts of trees (trunk, branches, leaves) for structural modeling

Built with Open3D, PyTorch, and mesh processing libraries

![QSM pipeline visualization](./imgs/cluster4_side_by_Side.png)

---


### 🌲 [`ArchiveTeam IAC`](https://github.com/wischmcj/archiveteam-digitalocean-IaC)
Infrastructure-as-code that deploys a modern observability stack and an arbitrary number of containerized applications across several remote machines. Docker is used for containerization and the observation stack consists of a Prometheus, Grafana, and a custom NodeJS metrics server. Utilized primarily for the community archive project [ArchiveTeam](https://wiki.archiveteam.org/) 

- Creates and configures observer and worker nodes on digital ocean droplets using OpenTofu, Ansible
- Configurable, enabling a dynamic number of: workers (e.g. droplets) within the cluster and containers within each worker


![Simplified Process Diagram](./imgs/archiveteam_small.png)

---

### ⚡ [`PenguaLab-IaC`](https://github.com/wischmcj/PenguaLab-IaC)
Infrastructure-as-code setup for deploying a variety of homelab software containers on a Kubernetes (k3s) cluster using Terraform, Ansible, and Helm.

- Built to support a distributed home architecture for running parallel modeling processes 
- Entirely defines my home network as code, allowing me to host a resilient but flexible suite of always-available tooling
---

### 🔄 [`ml_ops_tree_learn`](https://github.com/wischmcj/ml_ops_tree_learn)
A small MLOps tool for cloud deployment of the Tree Learn Unet model. Automated provisioning of Digital Ocean GPU droplets to allow for accessible CUDA friendly compute.

- Emulates workflows I use professionally for model delivery
- Exemplifies the power of ML Ops when combined with open-source ML research

---

### 🕸️ [`linkedInScraper`](https://github.com/wischmcj/linkedInScraper)
A DLT pipeline for pulling jobs for followed companies from LinkedIn. Likewise contains a Node app for automating the application to jobs in a list curated by the user.

- Showcases utility scripting and automated data collection
- Represents my knack for building tools to bridge information silos

---

## 🎯 What Drives Me

I'm deeply motivated by work that sits at the intersection of **data science**, **ecological systems**, and **open innovation**. Moreover, I strive to embody the principles of 'data-as-a-service' in my work - keeping my focus on the end users and the value my tools might provide.

---

📫 Feel free to connect with me:  
[LinkedIn](https://www.linkedin.com/in/collin-wischmeyer-b55659a4) • [GitHub](https://github.com/wischmcj) • cjwischmeyer@gmail.com  
