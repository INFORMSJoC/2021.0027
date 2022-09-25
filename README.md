# 2021.0027

[![INFORMS Journal on Computing  Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

This archive is distributed in association with the [INFORMS Journal on Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License (LICENSE).

The software and data in this repository are a snapshot of the software and data
that were used in the research reported on in the paper 
[An LSTM+ Model for Managing Epidemics: Using Population Mobility and Vulnerability for Forecasting COVID-19 Hospital Admissions](https://doi.org/) 
by A. Ray, W. Jank, K. Dutta, and M. Mullarkey. 

## Cite

To cite this software, please cite the [paper](https://doi.org/) using its DOI and the software itself using the following DOI.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7112004.svg)](https://doi.org/10.5281/zenodo.7112004)

Below is the BibTex for citing this version of the code.

```
@article{LSTMCovid,
  author =        {A. Ray, W. Jank, K. Dutta, and M. Mullarkey},
  publisher =     {INFORMS Journal on Computing},
  title =         {An LSTM+ Model for Managing Epidemics: Using Population Mobility and Vulnerability for Forecasting COVID-19 Hospital Admissions},
  year =          {2022},
  doi =           {10.5281/zenodo.7112004},
  note =           {https://github.com/INFORMSJoC/2021.0027}
}  
```

# Data for LSTM+ Model

This repository contains the anonymous datasets used for the case study in the LSTM+ model.

## Dataset

**MobilityData_Anonymized.csv**: Contains the mobility metrics, ROGSI, NULV, and NUDL at the zip code level. The county and zipcode information is anonymized.
**SocialVulnerabilityData_Anonymized.csv**: Contains the social vulnerability data at the county level.
**HospitalityData_Anonymized.csv**: Contains the inpatient admission data for the hospitals. The hospital names are anonymized.
**HospitalCountyMapping_Anonymized.csv**: Contains the hospital to county mapping, both data anonymized.

## Simulated Dataset

**sim_dynamicInput_train.csv**: Contains the simulated data for the dynamic features, *D*. The first column indicates the time index *t*, whereas the subsequent column headings indicate the entity index *i*. This file contains only the portion of the simulated data used for training.
**sim_dynamicInput_train.csv**: Same data as above but the holdout set for testing.
**sim_output_train.csv**: Contains the simulated data for the output, *O*. The first column indicates the time index *t*, whereas the subsequent column headings indicate the entity index *i*. This file contains only the portion of the simulated data used for training.
**sim_output_train.csv**: Same data as above but the holdout set for testing.
**sim_staticInput.csv**: This is the static or time-invariant data, *S*. The first column indicates entity index *i*, and the second column contains the corresponding value.
