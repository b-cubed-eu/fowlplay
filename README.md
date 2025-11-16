# fowlplay

<!-- badges: start -->
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12793619.svg)](https://doi.org/10.5281/zenodo.12793619)
<!-- badges: end -->

_A notebook to explore the value of sex data inside GBIF occurrence records for ducks (Anatidae)_

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)
![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)
![GBIF](https://img.shields.io/badge/Data-GBIF-lightgrey.svg)

---

## Overview  
**fowlplay** is an exploratory data-analysis notebook examining how often and how well the `sex` field is recorded for ducks (family *Anatidae*) in the Global Biodiversity Information Facility (GBIF).  
The notebook investigates:  
- The proportion of records containing sex information  
- Spatial and temporal patterns in annotation rates  
- Which species/datasets contribute usable sex metadata  
- Biases and implications for downstream research  

This repository aims to contribute to biodiversity data-quality assessment by highlighting the underexplored metadata dimensions available in GBIF.

---

## Why “fowlplay”?  
Sex information in biodiversity data is rarely used despite its potential importance for:  
- demographic models  
- life-history analyses  
- behavioural ecology  
- conservation assessments  

Ducks are a large, well-observed clade, making them ideal to explore the usefulness — and limitations — of GBIF’s sex metadata.

---

## Features  
- Fetch GBIF occurrences for ducks using a data cube download
- Filter and summarise sex-annotated records  
- Temporal trends and yearly changes  
- Species-level comparisons
- Optional spatial mapping with `geopandas`
- Interpretive discussion on biases and data gaps
