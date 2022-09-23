# Data for LSTM+ Model

This repository contains the anonymous datasets used for the case study in the LSTM+ model.

## Affiliated Paper

The affiliated paper of this repository is "An LSTM+ Model for Managing Epidemics: Using Population Mobility and Vulnerability for Forecasting COVID-19 Hospital Admissions".

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
