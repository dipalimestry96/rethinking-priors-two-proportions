# When Uniform Isn't Uniform: Rethinking Priors for the Difference of Two Proportions
## Authors

- **Dipali Vasudev Mestry**,
  Institute of Chemical Technology, Mumbai,  
  Email: dipalimestry96@gmail.com

- **Sujit K. Ghosh**,  
  NC State University,  
  Email: sujit.ghosh@ncsu.edu

- **Amiya R. Bhowmick**, 
  Institute of Chemical Technology, Mumbai,
  Email: ar.bhowmick@ictmumbai.edu.in

---

## Description

This repository contains all R codes used for the simulation studies and real data illustrations in the paper:

> "When Uniform Isn't Uniform: Rethinking Priors for the Difference of Two Proportions."
---

## Repository Structure
```
rethinking-priors-two-proportions/
│
├── simulation_independent_priors/
│     ├── Block_1_simulation_study.R
│     ├── Block_2_simulation_study.R
│     ├── Block_3_simulation_study.R
│     ├── Block_4_simulation_study.R
│     ├── Block_5_simulation_study.R
│     ├── Block_6_simulation_study.R
│     └── HPD_computation/
│           ├── HPD_Block_1.R
│           ├── HPD_Block_2.R
│           ├── HPD_Block_3.R
│           ├── HPD_Block_4.R
│           ├── HPD_Block_5.R
│           └── HPD_Block_6.R
│
├── simulation_dependent_prior/
│     ├── Block_1_dependent.R
│     ├── Block_2_dependent.R
│     ├── Block_3_dependent.R
│     ├── Block_4_dependent.R
│     ├── Block_5_dependent.R
│     └── Block_6_dependent.R
│
├── real_data/
│     ├── challenger_analysis.R
│     └── kras_analysis.R
│
└── README.md
```
---
## Requirements

R version 4.0 or higher with the following 
packages:

```r
install.packages(c("coda", "data.table", "ggplot2", "ggdist","Stat2Data"))
```

---

## Citation

If you use this code, please cite.
---
