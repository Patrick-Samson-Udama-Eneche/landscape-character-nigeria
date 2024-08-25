# LANDSCAPE CHARACTERIZATION OF NIGERIA

### Description

This repository is a collection of (python) codes that were used to perform the landscape characterization of Nigeria. While the notebooks only contain input dataset that were used for the assessment, all output/result obtained therefrom can be obtained directly from [Zenodo](https://www.futurelearn.com/courses/artificial-intelligence-for-earth-monitoring). 

### Notebooks in Order of Sequence

* Google Earth Engine Dataset: for Elevation, Landcover and Land Surface Temperature data acquisition - /GEE_Dataset/GEE_data_acq.ipynb. 
* Cluster Analysis: for landscape type and area identification/delineation - /cluster_analyses.ipynb
* Cluster Determination - used to determine optimal number of clusters based on Machine Learning - /cluster_determination.ipynb
* Landscape Structure Analysis - for analysing the composition and configuration of identified landscape characters: /landscape_stats.ipynb


**NOTE**

* Data on parent material (geology) was downloaded and preprocessed from [Nkwunonwo et al (2020)](https://doi.org/10.1016/j.dib.2020.105941) and [Salawu et al (2019)](https://doi.org/10.1007/s40948-019-00110-7).
* Climate of Nigeria was downloaded and preprocessed from [Ugwu, et al (2023)](https://doi.org/10.1016/j.sciaf.2023.e01670).
* This repository support Python 3.8 and later and all required libraries are stated at the beginning of each notebook.



### Cloning the repository

To clone this repository to your local directory, type:

``` shell
    git clone https://github......
```



## License

This code is licensed under an MIT license. See file LICENSE.txt for details on the usage and distribution terms.
