# DLMAIIAC Workbook: Task Summaries

## Notebooks Overview

### task_2_d_separation.ipynb
**Data type:** Real-world observational data  
**Data source:** `social_media_enagament_data.csv` (CSV file loaded in the notebook). Source and licensing information included in the data\NOTICE.txt file.

Explores the concept of d-separation in causal graphs using observational data. Demonstrates how to read and analyze data, construct a causal graph, and apply d-separation principles to identify conditional independencies using Python libraries such as `causallearn` and `dowhy`.

**Refutation tests used:**
- Placebo Treatment Refuter
- Random Common Cause Refuter
- Data Subset Refuter
- Bootstrap Refuter

### task_4_backdoor-criterion.ipynb
**Data type:** Simulated data  
**Data source:** Data generated within the notebook (simulated genetic and health variables)

Focuses on the backdoor criterion for identifying causal effects. Illustrates how to define a causal model, construct a DAG, and use DoWhy to identify and estimate causal effects by adjusting for confounders. Includes simulation and visualization of data, and discusses assumptions behind the backdoor adjustment.

**Refutation tests used:**
- Placebo Treatment Refuter
- Random Common Cause Refuter
- Data Subset Refuter
- Bootstrap Refuter

### task_5_rct_study.ipynb
**Data type:** Simulated observational data (emulating an RCT via matching)  
**Data source:** `student_performance_data.csv` (loaded from the data folder in the notebook). Source and licensing information included in the data\NOTICE.txt file.

Presents a workflow for analyzing a randomized controlled trial (RCT) study. Covers data preprocessing, feature selection, and propensity score matching to create balanced treatment and control groups. Applies the PC algorithm to check for confounding and runs RCT analysis to estimate treatment effects.

### task_6_frontdoor-criterion.ipynb
**Data type:** Simulated data  
**Data source:** Data generated within the notebook (simulated exercise, caloric burn, and weight loss variables)

Demonstrates the frontdoor criterion for causal inference in the presence of unmeasured confounding. Simulates data with a mediator, constructs a causal graph, and uses DoWhy to identify and estimate the causal effect via the frontdoor adjustment, including interpretation of results.

**Refutation tests used:**
- Placebo Treatment Refuter
- Dummy Outcome Refuter
- Data Subset Refuter
- Bootstrap Refuter
