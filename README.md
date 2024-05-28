# Figure1a.csv and Figure1b.csv
`HR`: Hazard Ratio

`CI`: 95% Confidence Interval

`down`: Lower Bound

`up`: Upper Bound

`case_group`: No. of patients (percent of case cohort)

`control_group`: No. of patients (percent of control cohort)

`blah`: Outcomes

# forest.r
This file plots the hazard ratios and 95% confidence intervals on a base-10 log scale.

Change read file `file.path(workdir,"Figure1a.csv")` (one-year outcomes in patients with colorectal cancer and comorbid type 2 diabetes mellitus) to `Figure1b.csv` to plot outcomes in patients with colorectal cancer and comorbid obesity.

## Technologies
Project is created with:
* R 4.2.2
* RStudio Version 2023.03.1+446
