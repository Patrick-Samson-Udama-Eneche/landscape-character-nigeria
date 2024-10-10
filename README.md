# Landscape Characterization of Nigeria

This repository contains a collection of Python scripts used for the landscape characterization of Nigeria, leveraging machine learning-based algorithms and spatial analysis techniques. The characterization focuses on the composition and configuration of Nigeria's biophysical landscape types/areas at a 1km resolution.

All input datasets required for this assessment are provided within the repository, while the output results and other resources (e.g. [Dashboard](https://doi.org/10.5281/zenodo.13880382), datasets, etc.) are available in our mirrored project on [Open Science Framework (OSF)](https://doi.org/10.17605/OSF.IO/E2K73). Kindly note that it is an ongoing research.

## Table of contents

* [Requirements](#Requirements)
* [Getting Started](#Getting-Started)
* [Notebooks](#notebooks)
* [Data and Methods](#data-and-methods)
* [Results](#results)
* [Usage](#usage)
* [Contribution/Collaboration](#how-to-contributecollaborate)


## Requirements

The results were produced using Python 3.12.3 and Jupyter Notebook in the following test environment:

```
Operating system: Windows x86_64
CPU: 13th Gen Intel(R) Core(TM) i7-13700H (14 Cores | 20 Log. Processors)
memory (RAM): 16GB
disk storage: 1TB
GPU: NVIDIA RTX A500
```

## Getting Started

To get started with this project, follow the steps below to set up your environment and install the necessary dependencies.

### Prerequisites

#### Python

Make sure Python 3.12 or later is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

#### Setting Up a Virtual Environment
```
It is recommended to create a virtual environment to isolate project dependencies. See the [link](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)
```
### Install Libraries/Dependencies
```
Run the following command to install all the required libraries:

pip install -r requirements.txt

```

## Notebooks

This repository is organized into four distinct Jupyter notebooks; each handling a specific aspect of the research:

### 1. Google Earth Engine Dataset Acquisition

* Notebook: /GEE_Dataset/GEE_data_acq.ipynb

* Purpose: Acquires elevation, land cover, and Land Surface Temperature (LST) data.

* Requirements: Google authentication is necessary.


### 2. Cluster Analysis

* Notebook: /cluster_analyses.ipynb

* Purpose: Identifies and delineates landscape types and areas via clustering techniques.


### 3. Cluster Determination

* Notebook: /cluster_determination.ipynb

* Purpose: Determines the optimal number of clusters using machine learning algorithms.

* Note: Depending on your system's configuration, this notebook may require significant processing time.


### 4. Landscape Structure Analysis

* Notebook: /landscape_stats.ipynb

* Purpose: Analyze the composition and configuration of the identified landscape characters.



## Data and Methods

Based on the European Landscape Classification [LANMAP Typology](http://dx.doi.org/10.1016/j.ecolind.2009.03.018), the following dataset are used:
* Parent material (geology) was downloaded from [Nkwunonwo et al (2021)](https://data.mendeley.com/datasets/zmrt6k83wk/1) and preprocessed.
* Climate of Nigeria was downloaded from [Ugwu, et al (2023)](https://doi.org/10.1016/j.sciaf.2023.e01670) and preprocessed.
* Elevation was obtained from Google Earth [data catalogue](https://developers.google.com/earth-engine/datasets/catalog/CGIAR_SRTM90_V4#description) or from the [official website](https://srtm.csi.cgiar.org).
* Landcover data is from Google Earth [data catalogue](https://developers.google.com/earth-engine/datasets/catalog/ESA_WorldCover_v200) or from the [The European Space Agency (ESA)](https://esa-worldcover.org).
* Lastly, for an extended description of landscape characters, we made use of The Terra Moderate Resolution Imaging Spectroradiometer (MODIS) Land Surface Temperature/Emissivity Daily (MOD11A1) Version 6.1 product which is accessible via Google Earth [data catalogue](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD11A1#dois) or use the [link](https://doi.org/10.5067/MODIS/MOD11A1.061).

![flowchart_1](https://github.com/user-attachments/assets/508e5006-f583-4249-bf4f-41d399527d69)


## Results

Landscape Character of Nigeria

![image](https://github.com/user-attachments/assets/b3a24f93-b883-48f2-9528-1f693dd3ead4)

## Dashboard
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13880382.svg)](https://doi.org/10.5281/zenodo.13880382)
![Dashboard_Nigeria_landscape_character](https://github.com/user-attachments/assets/b582059a-c5dd-4f15-963b-fc1c7bcac6f6)



## Usage
To replicate the analysis or explore the input dataset, clone this repository and ensure all dependencies are installed as stated above.

To clone this repository to your local directory, type:

``` bash
    git clone https://github.com/PatrickEneche/landscape_character_nigeria.git.
```


### License

This repository is licensed under an [CC-By Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode). See the License.txt for details on the terms of usage and (re)distribution.


## How to contribute/collaborate

Thank you for your interest to contribute/collaborate. Kindly send an email to p.s.u.eneche@utwente.nl

## Additional information

For more information please visit the project page on the [Open Science Framework (OSF)](https://doi.org/10.17605/OSF.IO/E2K73)