# Flood Risk Dynamics

This repository contains the codebase for the research paper:

**Large-scale flood risk analysis of culvert infrastructure serving 3000 catchments in New York State**

## Overview

This project investigates the spatio-temporal dynamics of flood risk within New York state road networks, focusing on the performance and behavior of large culvert drainage systems. It includes data preprocessing, hydrologic and hydraulic modeling, model validation, risk analysis, and visualization workflows used in the study.

<p float="left">
  <img src="Image/culvert_1.PNG" alt="Culvert 1" width="45%" />
  <img src="Image/culvert_2.PNG" alt="Culvert 2" width="25.5%" />
</p>
<p style="text-align: center; font-style: italic; font-size: 10px;">
  Figure: Field photographs of culverts observed during a site visit to Upstate New York.
</p>

## Website:
The results of this study are visually hosted on this website :

## Repository Contents

- `Data preprocessing`: Prepares raw data for parallel computation by cleaning, formatting, and organizing it appropriately.
- `Hydrologic model`: Performs watershed delineation, Curve Number (CN) calculation, and peak hydrologic flow estimation.
- `Hydraulic model`: Calculates the hydraulic capacity of the culverts.
- `Validation`:  Validates each component, including watershed delineation, CN values, peak flow estimations, and hydraulic capacity.
- `Result`: Conducts risk assessment and visualizes both the temporal and spatial dynamics of the risk.

## Data Access

### Input and Output Data

All input and output files required to run the code are hosted on **Zenodo**:

📁 **Zenodo DOI**: [10.5281/zenodo.15306498](https://doi.org/10.5281/zenodo.15306498)

Download and extract the files to the appropriate directories as outlined in the documentation within the repository.

📁 **Figshare DOI**: *To be added*  
_Replace this line with the actual link or DOI once available._

## Getting Started

To run the analysis:

1. Clone the repository:
   ```bash
   git clone https:https://github.com/omidemam/flood_risk_dynamics.git
   cd flood_risk_dynamics

## 📬 Contact

For questions, feedback, or collaboration opportunities, please email me at: [omid.emamjomehzadeh@nyu.edu](mailto:omid.emamjomehzadeh@nyu.edu)


   
## 📚 Citation

If you use this repository in your research or projects, please cite it as follows:

BibTeX format:

```bibtex
@misc{emamjomehzadeh2025flood,
  author       = {Omid Emamjomehzadeh},
  title        = {Flood Risk Dynamics},
  year         = {2025},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {\url{https://github.com/omidemam/flood_risk_dynamics}},
}


