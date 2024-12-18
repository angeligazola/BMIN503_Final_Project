# Exploring the Association Between BMI and Early-Onset Colorectal Cancer
**by Antonia Angeli Gazola as part of her Master in Biomedical Informatics studies at the University of Pennsylvania**  

- **Course:** 5030-401 202430 Data Science For Biomedical Informatics
- **Course Professor:** Prof. Dr. Blanca Himes  
- **Advisors:** Prof. Dr. Gary Weissman and Nicholas Bishop, BA

This repository contains the work associated with my final project for the **5030 Data Science** course as part of the **Master's in Biomedical Informatics** program at the **Perelman School of Medicine**, **University of Pennsylvania**. The project focuses on investigating the association between **Body Mass Index (BMI)** and the **age of diagnosis of colorectal cancer**.

### Project Overview

The goal of this project is to explore whether higher BMI is associated with an earlier onset of colorectal cancer, considering the increasing incidence of early-onset colorectal cancer. By analyzing the **MSK, JNCI 2021 colorectal cancer dataset** from **cBioPortal**, I aim to investigate how obesity (per BMI) may be associated with the age of diagnosis of colorectal cancer in colorectal cancer patients.

The project's analysis is divided into three main sections:

1. **Descriptive Statistics**
2. **Linear Regressions**
3. **Logistic Regressions**

The primary focus is in the association between BMI and age at diagnosis. Secondarily, the analysis will explore relationships between BMI, age at diagnosis, and other variables, incorporating those as predictors and interactors in the models.

The project's report is being written in R language in a quarto document in RStudio, containing the following structure: overview, introduction, methods, results, discussion and limitations, conclusion and references.

### Repository Overview

This repository includes:

- **README.md**: overview of the project and repository contents.  
- **5030_final_project_presentation_Antonia_ANGELI_GAZOLA.pptx**: short power point slide show presentation of my project for class
- **final_project_ANGELIGAZOLA.qmd**: final project quarto document with all project sections 
- **final_project_ANGELIGAZOLA.html**: rendered HTML version of the final project for better visualization.
- **5030_references.bib**: bibTeX file with references used to write the report, created through Mendeley.


### Guidance

My project advisors are:
- **Prof. Dr. Gary Weissman**, Assistant Professor in Pulmonary and Critical Care Medicine and Informatics, who provided insight into refining the research question and data analysis approach from a clinical perspective.
- **Nicholas Bishop, BA**, Clinical Research Coordinator, who assisted in developing the methodological approach and visualizations for the dataset.

Their expertise has been instrumental in shaping the direction and execution of this project.


### Instructions for Viewing and Running the Project

To view the latest draft of the project or to open and run the files locally, follow these instructions:

- #### View the Rendered HTML:
Open the `final_project_ANGELIGAZOLA.html` file in your web browser to view the latest draft with full formatting and visualizations.

- #### Open and Run Quarto Files Locally:
1. Install **R and RStudio** on your system. Follow the installation instructions on the [RStudio website](https://rstudio-education.github.io/hopr/starting.html).
2. Clone this repository to your local computer using Git.
3. Use **RStudio** to open the .qmd file and explore the project. 
4. To be able to run the document, please download the dataset [MSK Colorectal Cancer dataset (MSK, JNCI 2021)](https://frontend.cbioportal.org/study/summary?id=crc_eo_2020) from cBioPortal,
and keep it in your desktop area.
5. To be able to see the references when rendering, please download the .bib reference file as well.

