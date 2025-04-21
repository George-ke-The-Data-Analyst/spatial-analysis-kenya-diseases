# Spatial Analysis of Major Disease Incidence in Kenya
Spatial analysis of malaria, TB, HIV and asthma incidence across Kenya’s counties

**Description**  
This R project maps and analyses the county‑level incidence of four key diseases—Malaria, Tuberculosis (TB), HIV, and Asthma—across Kenya’s 47 counties. Using administrative‐boundary shapefiles and a WHO case dataset, it produces choropleth maps and identifies regional hotspots to inform public health interventions. :contentReference[oaicite:0]{index=0}&#8203;:contentReference[oaicite:1]{index=1}

## Table of Contents

1. [Prerequisites](#prerequisites)  
2. [Installation](#installation)  
3. [Data](#data)  
4. [Usage](#usage)  
5. [Project Structure](#project-structure)  
6. [Results](#results)  
7. [License](#license)  
8. [Contact](#contact)

---

### Prerequisites

- **R** (version ≥ 4.2.0)  
- **R packages**:  
  ```r
  install.packages(c(
    "sf", "spData", "ggplot2", "dplyr", "tidyverse",
    "spdep", "tmap", "sp", "RColorBrewer", "leaflet"
  ))
Results
After running plot_disease_maps.R, check outputs/figures/ for:

Malaria_cases_by_county.png

TB_cases_by_county.png

HIV_cases_by_county.png

Asthma_cases_by_county.png
