# Synthetic Research Identifiable Files (RIF) Validation 
This repository contains Jupyter notebooks used to validate synthetic data and provide examples illustrating use of the data.

## Contents

| File | Description |
|------|-------------|
| beneficiary_final_demographics | A notebook visualizing beneficiary demographic data from the `beneficiary_2022.csv` file. |
|beneficiary_population_count_chart.ipynb | A notebook visualizing the beneficiary population by year. |
| chronic_conditions_apriori | A notebook identifying association rules using the apriori algorithm. |
| claim_lines_per_claim | A notebook visualizing beneficiary claim lines per claim distributions and calculating average claim lines per claim.|
| claimants_by_service_type | A notebook calculating the number of unique beneficiaries. |
| cms_user_manual_transformation_and_analysis | A notebook containing an example of how to load and read synthea data. |
| length_of_stay | A notebook calculating inpatient, SNF, and hospice length of stay (LOS) in days.  |
| reimbursements | A notebook visualizing claim payment amount (`CLM_PMT_AMT`) distributions across service types.  |
| requirements | A text file listing all dependencies in the repository. |
|synthetic_feature_selection_input.ipynb | A notebook that constructs an input dataframe to be used for feature selection. |
| synthetic_sdoh_feature_selection_limit_feature_class.ipynb | A notebook identifying features that contribute most to the 30 day readmissions target variable. |
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