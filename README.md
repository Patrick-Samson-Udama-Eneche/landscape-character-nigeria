# Landscape Characterization of Nigeria

## Description
This repository contains a collection of Python scripts used for the landscape characterization of Nigeria, leveraging machine learning-based algorithms and spatial analysis techniques. The characterization focuses on the composition and configuration of Nigeria's biophysical landscape types/areas at a 1km resolution.

All input datasets required for this assessment are provided within the repository, while the outputs/results are available for download from [Zenodo](https:zenodo....). This repository is compatible with Python 3.8 and later versions, and all necessary libraries are listed at the beginning of each notebook.

## Notebooks Overview

This repository is organized into four distinct Jupyter notebooks, each handling a specific aspect of the research:

### 1. Google Earth Engine Dataset Acquisition

* Notebook: /GEE_Dataset/GEE_data_acq.ipynb

* Purpose: Acquires elevation, land cover, and Land Surface Temperature (LST) data.

* Requirements: Google authentication is necessary.


### 2. Cluster Analysis

* Notebook: /cluster_analyses.ipynb

* Purpose: Identifies and delineates landscape types and areas through clustering techniques.


### 3. Cluster Determination

* Notebook: /cluster_determination.ipynb

* Purpose: Determines the optimal number of clusters using machine learning algorithms.

* Note: Depending on your system's capabilities, this notebook may require significant processing time.


### 4. Landscape Structure Analysis

* Notebook: /landscape_stats.ipynb

* Purpose: Analyze the composition and configuration of the identified landscape characters.



## Data

Based on the European Landscape Classification [LANMAP Typology](http://dx.doi.org/10.1016/j.ecolind.2009.03.018), the following dataset are used:
* Parent material (geology) was downloaded from [Nkwunonwo et al (2020)](https://doi.org/10.1016/j.dib.2020.105941) and [Salawu et al (2019)](https://doi.org/10.1007/s40948-019-00110-7), and preprocessed.
* Climate of Nigeria was downloaded from [Ugwu, et al (2023)](https://doi.org/10.1016/j.sciaf.2023.e01670) and preprocessed.
* Elevation was obtained from Google Earth [data catalogue](https://developers.google.com/earth-engine/datasets/catalog/CGIAR_SRTM90_V4#description) or from the [official website](https://srtm.csi.cgiar.org).
* Landcover data is from Google Earth [data catalogue](https://developers.google.com/earth-engine/datasets/catalog/ESA_WorldCover_v200) or from the [The European Space Agency (ESA)](https://esa-worldcover.org).
* Lastly, for an extended description of landscape characters, we made use of The Terra Moderate Resolution Imaging Spectroradiometer (MODIS) Land Surface Temperature/Emissivity Daily (MOD11A1) Version 6.1 product which is accessible via Google Earth [data catalogue](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD11A1#dois) or use the [link](https://doi.org/10.5067/MODIS/MOD11A1.061).

## Result Preview

Landscape Character of Nigeria

![image](https://github.com/user-attachments/assets/b3a24f93-b883-48f2-9528-1f693dd3ead4)

## Usage
To replicate the analysis or explore the input dataset, clone this repository and ensure all dependencies are installed. Each notebook contains detailed instructions for execution.

To clone this repository to your local directory, type:

``` bash
    git clone https://github.com/PatrickEneche/landscape_character_nigeria.git.
```




## License

This code is licensed under an MIT license. See file LICENSE.txt for details on the usage and distribution terms.
