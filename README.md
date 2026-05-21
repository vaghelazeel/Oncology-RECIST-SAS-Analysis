# Oncology Clinical Trial - Tumour Response Analysis (RECIST 1.1)

## Overview
This project simulates an oncology clinical trial dataset and applies RECIST 1.1 criteria to classify patient tumour responses. Built using SAS OnDemand for Academics.

## Background
RECIST (Response Evaluation Criteria in Solid Tumours) version 1.1 is the standard framework used in oncology clinical trials to assess how well a patient responds to treatment.

Response categories:
- CR (Complete Response) - tumour completely disappeared
- PR (Partial Response) - tumour shrunk by 30% or more
- SD (Stable Disease) - no significant change
- PD (Progressive Disease) - tumour grew by 20% or more

## Dataset
- 15 simulated patients
- Two treatment arms: TRT_A and TRT_B
- Tumour measurements at Baseline, Week 8, and Week 16
- Measurement used: Sum of Longest Diameters (SLD) in mm

## Analysis Modules

| Module | Description |
|--------|-------------|
| 1 | Patient demographics and baseline tumour measurements |
| 2 | Follow-up measurements at Week 8 and Week 16 |
| 3 | RECIST 1.1 response classification logic |
| 4 | Summary statistics by treatment arm |
| 5 | Waterfall plot visualisation |
| 6 | Objective Response Rate report |

## Key Findings
- TRT_A achieved 87.5% Objective Response Rate (7/8 patients)
- TRT_B achieved 28.6% Objective Response Rate (2/7 patients)
- TRT_A mean tumour reduction: -46.8%
- TRT_B mean tumour reduction: -11.7%

## Tools Used
- SAS OnDemand for Academics
- PROC FREQ, PROC MEANS, PROC SGPLOT
- DATA step programming

## Author
Zeel Vaghela
MSc Bioinformatics, Teesside University
linkedin.com/in/zeel-vaghela
