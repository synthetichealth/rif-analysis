# Synthetic Research Identifiable (RIF) Validation 
This repository contains Jupyter notebooks used to validate synthetic data and provide examples illustrating use of the data.

## Contents

| File | Description |
|------|-------------|
| CMS_User_Manual_-_Transformation_and_Analysis | A notebook containing an example of how to load and read synthea data. |
| beneificary_final_demographics | A notebook visualizing beneficiary demographic data from the `beneficiary_final.csv` file |
| chronic_conditions_apriori | A notebook identifying association rules using the apriori alorithm. |
| claim_lines_per_claim | A notebook visualizing beneficiary claim lines per claim distributions and calculating average claim lines per claim.|
| claimants_by_service_type | A notebook calculating the number of unique beneficiaries. |
| length_of_stay | A notebook calculating inpatient, SNF, and hospice length of stay (LOS) in days.  |
| reimbursements | A notebook visualizing claim payment amount (`CLM_PMT_AMT`) distributions across service types.  |
| requirements | A text file listing all dependencies in the repository. |
| synthetic_readmissions_race_only_dm | A notebook predicting 30, 60, and 90-day hospital readmissions using logistic regression. |
| synthetic_readmissions_sdoh_with_race_dm | A notebook predicting 30, 60, and 90-day hospital readmissions using logistic regression. This notebook does not contain `BENE_RACE_CD` as a predictor. |
| unique_claims_per_beneficiary | A notebook visualizing unique claims per beneficiary distributions. |

## Requirements 

These notebooks require [Jupyter](https://jupyter.org/about). 

All dependencies can be found in the `requirements.txt` file, which you can configure using `pip`:

```
pip install -r requirements.txt
```

## Data 

The synthetic datasets used in this repository can be downloaded from data.gov. Copy the data files into the "data" folder on this repository.

# License

Copyright 2022 The MITRE Corporation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.