# Repository for:
**Title of the paper:** Is There New Physics Beyond 30 TeV in the BOAT? 

**Authors:** Filip Rescic, Luis Recabarren Vergara, Michele Doro, Tomislav Terzić 

**ArXiv:** [2511.15542](https://arxiv.org/abs/2511.15542)  

---

## Overview

This repository contains the **data tables (.csv)** used to generate Figures 1 and 3 presented in the above paper.  
Each CSV file corresponds to a single collection of points from the manuscript and includes the processed numerical values used to produce the results.

The goal of this repository is to enable transparency, reproducibility, and reuse of the data in further research.

Acronyms: Special Relativity (SR), Lorentz Invariance Violation (LIV), Gamma-Ray Burst (GRB)

---

## Repository Contents

| Filename | Description |
|---------|---------------|
| `boat_data_5_14.csv`, `boat_data_14_22.csv`, `boat_data_22_100.csv`, `boat_data_100_674.csv`, `boat_data_674_1774.csv` | 5 set of points for 5 time intervals (Fig. 1). |
| `boat_sal_sr.csv` | Attenuation table for GRB 221009A, in the case of SR (Fig. 1). |
| `boat_sal_liv.csv` | Attenuation table for GRB 221009A, in the case of LIV (Fig. 1). |
| `pks2155_sal_sr.csv` | Attenuation table for PKS2155-304, in the case of SR (Fig. 3). |
| `pks2155_sal_liv.csv` | Attenuation table for PKS2155-304, in the case of LIV (Fig. 3). |
| `swgo_1yrsensitivity_WP.csv`, `swgo_5yrsensitivity_WP.csv` | 1 and 5 year sensitivity of SWGO, respectively (Fig. 3). |
| `lhaaso_1yrsensitivity.csv` | LHAASO 1 year sensitivity (Fig. 1). |


SWGO Sensitivity:  Ref. [33](https://arxiv.org/abs/2506.01786)

LHAASO Sensitivity: Ref. [32](https://iopscience.iop.org/article/10.1088/1742-6596/718/5/052043)

EBL model: Saldana-Lopez et al. (2021), Ref. [4](https://academic.oup.com/mnras/article/507/4/5144/6359154), ArXiv: [2012.03035](https://arxiv.org/abs/2012.03035)

---

## Column Descriptions and Units

| Filename | Column titles | Units |
|-------------|---------|-------|
| `boat_data_5_14.csv`, `boat_data_14_22.csv`, `boat_data_22_100.csv`, `boat_data_100_674.csv`, `boat_data_674_1774.csv` | E / E2dNdE | TeV / ergcm-2s-1|
| `boat_sal_sr.csv` | atten_sr / energy | # / eV|
| `boat_sal_liv.csv` | atten_LIV_lambda_1 / atten_LIV_lambda_2 / atten_LIV_lambda_3 / atten_LIV_lambda_4 / atten_LIV_lambda_5 / atten_LIV_lambda_6 / atten_LIV_lambda_7 / energy | # / # / # / # / # / # / # / eV|
| `pks2155_sal_sr.csv` | atten_sr / energy | # / eV|
| `pks2155_sal_liv.csv` | atten_LIV_lambda_1 / atten_LIV_lambda_2 / atten_LIV_lambda_3 / atten_LIV_lambda_4 / energy| # / # / # / # / eV|
| `swgo_1yrsensitivity_WP.csv`, `swgo_5yrsensitivity_WP.csv` | E / E2dndE | TeV / TeVcm-2s-1 |
| `lhaaso_1yrsensitivity.csv` | E / E2dNdE | TeV / ergcm-2s-1|

**N.B. :** the attenuation ('atten') columns provide the attenuation factor (survival probability) that multiplies the intrinsic flux in Eq. (2).

