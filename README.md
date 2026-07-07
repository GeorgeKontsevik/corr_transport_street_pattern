# corr_transport_street_pattern

---

[![OSA-improved](https://img.shields.io/badge/improved%20by-OSA-yellow)](https://github.com/aimclub/OSA)

Built with:

![folium](https://img.shields.io/badge/Folium-77B829.svg?style={0}&logo=Folium&logoColor=white)
![jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style={0}&logo=Jupyter&logoColor=white)
![numpy](https://img.shields.io/badge/NumPy-013243.svg?style={0}&logo=NumPy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458.svg?style={0}&logo=pandas&logoColor=white)
![scipy](https://img.shields.io/badge/SciPy-8CAAE6.svg?style={0}&logo=SciPy&logoColor=white)
![tqdm](https://img.shields.io/badge/tqdm-FFC107.svg?style={0}&logo=tqdm&logoColor=black)

---

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Citation](#citation)

---

## Overview

This project is a notebook-centric Python workspace for exploratory analysis of how transport-related indicators relate to street-pattern structure. It is aimed at researchers and data scientists who want to reproduce or extend correlation-oriented experiments in an interactive environment. The repository centers on Jupyter-based analysis workflows rather than a packaged application, and newcomers should use the Getting Started instructions to run the notebooks and inspect the results.

---

## Installation

**Prerequisites:** requires Python >=3.11

Install corr_transport_street_pattern using one of the following methods:

**Build from source:**

1. Clone the corr_transport_street_pattern repository:
```sh
git clone https://github.com/GeorgeKontsevik/corr_transport_street_pattern
```

2. Navigate to the project directory:
```sh
cd corr_transport_street_pattern
```

3. Install the project dependencies:

```sh
pip install -r requirements.txt
```

---

## Getting Started

Prerequisites:

- Python with Jupyter notebook support.
- The notebooks use `geopandas`, `pandas`, `numpy`, `osmnx`, `networkx`, `shapely`, `matplotlib`, `scipy`, `tqdm`, `pickle`, `json`, and `torch` / `torch_geometric` in the shown setup cells.
- Notebook runs expect local geospatial inputs and serialized helper artifacts referenced in the notebooks.

1. Open the notebook you want to reproduce, such as `cleaned_ver.ipynb`, `pattern_mode_corr.ipynb`, or `pt_exp.ipynb`.
2. Install the packages used in the notebook setup cells before running it. The notebooks show `pip install` commands for `huggingface_hub`, `geopandas`, `osmnx`, `torch_geometric`, `folium>=0.12`, `matplotlib`, and `mapclassify`.
3. Run the import and data-loading cells from top to bottom so the notebook can read the required geospatial inputs and serialized dictionaries or graphs.
4. If you are working in `pattern_mode_corr.ipynb`, follow the notebook cells that filter the polygon data, convert the CRS, and prepare the `geo_place` values before downstream analysis.
5. Continue executing the analysis cells in order to generate the correlation and visualization outputs.

---

## Documentation

A detailed corr_transport_street_pattern description is available [here](https://github.com/GeorgeKontsevik/corr_transport_street_pattern/tree/main/docs).

---

## Contributing

- **[Report Issues](https://github.com/GeorgeKontsevik/corr_transport_street_pattern/issues)**: Submit bugs found or log feature requests for the project.

- **[Submit Pull Requests](https://github.com/GeorgeKontsevik/corr_transport_street_pattern/tree/main/CONTRIBUTING.md)**: To learn more about making a contribution to corr_transport_street_pattern.

---

## Citation

If you use this software, please cite it as below.

### APA format:

    GeorgeKontsevik (2026). corr_transport_street_pattern repository [Computer software]. https://github.com/GeorgeKontsevik/corr_transport_street_pattern

### BibTeX format:

    @misc{corr_transport_street_pattern,

        author = {GeorgeKontsevik},

        title = {corr_transport_street_pattern repository},

        year = {2026},

        publisher = {github.com},

        journal = {github.com repository},

        howpublished = {\url{https://github.com/GeorgeKontsevik/corr_transport_street_pattern}},

        url = {https://github.com/GeorgeKontsevik/corr_transport_street_pattern}

    }

---