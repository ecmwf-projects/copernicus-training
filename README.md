# Training on data from the Copernicus Climate Change Service (C3S) and Atmosphere Monitoring Service (CAMS)

This repository hosts Jupyter notebook training material for the [Copernicus Climate Change Service (C3S)](https://climate.copernicus.eu/) and the [Copernicus Atmosphere Monitoring Service (CAMS)](https://atmosphere.copernicus.eu/). 

The training is designed for everyone who is interested in data from the two Copernicus services C3S and CAMS and has the following objectives:
* to showcase how data can be accessed via the [Climate Data Store (CDS)](https://cds.climate.copernicus.eu/cdsapp#!/home) and the [Atmosphere Data Store (ADS)](https://ads.atmosphere.copernicus.eu/#!/home), and
* to offer `example applications` and `analysis workflows` for different data types

## Course outline
The course is structured in two main parts and each part contains introduction and data overview notebooks as well as practical workflows.

### Training on C3S data

#### Introduction and data overview notebooks
* [100 - Climate Data Store - Introduction](./100_climate_data_store_intro.ipynb)
* [101 - C3S data - Overview](./101_c3s_data_intro.ipynb)

#### Application examples - Climate reanalysis data
* [111 - Climate reanalysis - Climatologies and anomalies](./111_c3s_climatologies_anomalies.ipynb)
* [112 - Climate reanalysis - Climate extremes](./112_c3s_climate_extremes.ipynb)
* [113 - Climate reanalysis - Climate indices](./113_c3s_climate_indices.ipynb)

#### Application examples - Seasonal forecasts
* [121_- Seasonal forecasts - Anomalies](./121_c3s_seasonal_forecasts_anomalies.ipynb)
* [122 - Seasonal forecasts - Bias correction](./122_c3s_seasonal_forecasts_bias_correction.ipynb)

#### Application examples - Climate projections
* [131 - CMIP6 Global climate projections](./131_c3s_cmip6_global_climate_projections.ipynb)
* [132 - CORDEX Region climate projections](./122_c3s_cordex_regional_climate_projections.ipynb)


### Training on CAMS data

#### Introduction to the Atmosphere Data Store
* [200 - Atmosphere Data Store - Introduction](./200_atmosphere_data_store_intro.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://hub-binder.mybinder.ovh/user/ecmwf-projects--rnicus-training-ulg9z83u/lab/tree/200_atmosphere_data_store_intro.ipynb) or view a static version via [**nbviewer**](https://nbviewer.org/github/ecmwf-projects/copernicus-training/blob/master/200_atmosphere_data_store_intro.ipynb)

#### Application examples
* [211 - CAMS wildfire emissions](./211_cams_fire_monitoring.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://hub-binder.mybinder.ovh/user/ecmwf-projects--rnicus-training-ulg9z83u/lab/tree/211_cams_fire_monitoring.ipynb) or view a static version via [**nbviewer**](https://nbviewer.org/github/ecmwf-projects/copernicus-training/blob/master/211_cams_fire_monitoring.ipynb)
* [212 - CAMS dust monitoring](./212_cams_dust_monitoring.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://hub-binder.mybinder.ovh/user/ecmwf-projects--rnicus-training-ulg9z83u/lab/tree/212_cams_dust_monitoring.ipynb) or view a static version via [**nbviewer**](https://nbviewer.org/github/ecmwf-projects/copernicus-training/blob/master/212_cams_dust_monitoring.ipynb)
* [213 - CAMS global reanalysis (EAC4) monthly averaged fields](./213_cams_global_reanalysis.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://hub-binder.mybinder.ovh/user/ecmwf-projects--rnicus-training-ulg9z83u/lab/tree/213_cams_global_reanalysis.ipynb) or view a static version via [**nbviewer**](https://nbviewer.org/github/ecmwf-projects/copernicus-training/blob/master/213_cams_global_reanalysis.ipynb)
* [214 - CAMS cross-section plot of sulphur dioxide (SO<sub>2</sub>) for La Palma volcanic eruption in October 2021](./214_cams_vertical_cross_section_volcanic_eruption.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://hub-binder.mybinder.ovh/user/ecmwf-projects--rnicus-training-ulg9z83u/lab/tree/214_cams_vertical_cross_section_volcanic_eruption.ipynb) or view a static version via [**nbviewer**](https://nbviewer.org/github/ecmwf-projects/copernicus-training/blob/master/214_cams_vertical_cross_section_volcanic_eruption.ipynb)
* [215 - CAMS European air quality index (EAQI](./215_cams_european_air_quality_index.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://hub-binder.mybinder.ovh/user/ecmwf-projects--rnicus-training-ulg9z83u/lab/tree/215_cams_european_air_quality_index.ipynb) or view a static version via [**nbviewer**](https://nbviewer.org/github/ecmwf-projects/copernicus-training/blob/master/215_european_air_quality_index.ipynb)


## How to use these training modules
This training material is made freely available on the [ecmwf-projects](https://github.com/ecmwf-projects) Github space under a [Apache 2.0 license](./LICENSE). There are several ways how you can use these training modules:
* [**nbviewer**](https://nbviewer.org/github/ecmwf-projects/copernicus-training/blob/master/000_index.ipynb) - Static and good rendering of the notebooks
* [**Colab**]()
* [**Binder**]([![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ecmwf-projects/copernicus-training/HEAD))
* **Clone this repo** and run the notebooks on your local Jupyter notebook server. If you wish you let run the material locally, you can go to the next section, which describes how to reproduce the setup on your local machine.


## Reproduce the training environment locally
In case you wish to reproduce the course modules locally on your computer, you will require the following Python version and Python packages:
* Python version: **Python3.8**
* Python packages: see requirements.txt

You can install the required Python packages with the following command in a terminal: `pip install -r requirements.txt`.

